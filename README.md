# Git as a Group

## **Step 1.) Visualizing Git**

http://git-school.github.io/visualizing-git/

### Part 1.) group divies out responsibilities

**(hint: make branches named after features)**

- git checkout -b login
- git checkout -b server
- git checkout -b database

### Part 2.) Commit

- **database person**

  - git commit -m 'added database'

- **login person**

  - git checkout login
  - git commit -m 'added initial inputs'

- **server-person**
  - git checkout server
  - git commit -m 'added express and body parser'
  - git commit -m 'added all endpoint, ready to merge'

### Part 3.) Merge

- git checkout master
- merge login
- merge server
- merger database

### Part 4.) looking at old commits

- git log

## **step2.) Git with your group!**

In this part we are going to have you get together with your teammates and practice pushing and pulling and dealing with merge conflicts

[Merge Conflicts](https://help.github.com/en/articles/about-merge-conflicts) happen when you merge branches that have competing commits, and Git needs your help to decide which changes to incorporate in the final merge.

**Hint:**

```
 If you have a merge conflict on the command line, you cannot push your local changes to GitHub until you resolve the merge conflict locally on your computer. If you try merging branches on the command line that have a merge conflict, you'll get an error message.
```

### Part 1.) Create the repository

- 1 teammate will create the repository
  - add your other teamates as collaborators
  - your teammates will need to accept your invitation before they can push
- 2 The rest of the team should clone the repository to thier local machine
  - you do not need to fork the project
- 3 everyone write out 6 days of christmas
  - git add .
  - git commit -m 'first commit'
  - git push

only one person's commit will actually make it to github, the rest of the team will need to run `git pull` to get the most recent changes and, you should recieve a merge conflict where there are 2 competing code statements that are competeing for the same line

you should talk with your teamates to choose which line of code should be the one to keep and which one can be discarded
