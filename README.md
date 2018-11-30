# Git as a Group

## **Visualizing Git**

http://git-school.github.io/visualizing-git/

## Part 1.) group divies out responsibilities

**(hint: make branches named after features)**

-   git checkout -b login
-   git checkout -b server
-   git checkout -b database

## Part 2.) Commit

-   **database person**

    -   git commit -m 'added database'

-   **login person**

    -   git checkout login
    -   git commit -m 'added initial inputs'

-   **server-person**
    -   git checkout server
    -   git commit -m 'added express and body parser'
    -   git commit -m 'added all endpoint, ready to merge'

## Part 3.) Merge

-   git checkout master
-   merge login
-   merge server
-   merger database

## Part 4.) looking at old commits

-   git log
