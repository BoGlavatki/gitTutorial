# gitTutorial
<h2>All About Working with Version Control.</h2>

## git log --oneline --decorate  
````
git log --oneline --decorate 
````

wohin die Zeiger der Branches zeigen. Diese Option wird --decorate genannt.

## git branch <name of new branch>
````
git branch <name of new branch>
````


## git checkout <name of branch>
````
git checkout <name of branch>
````

## git checkout branch <name of new branch>
````
git checkout branch <name of new branch>
````
## git merge <name of merged branch>
````
git merge <name of merged branch>
—abort 
—continue

````
## git branch
List of branches
````
git branch
````

Last commit 
`````
git branch -v
`````

## merge 
1# Test of existing branch -a for all (remote/local)
````
git branche -a
`````
2# to the main branch checkout
`````
git branch checkout main
`````
3# pull origin main
Configurations:
`````
Hinweis:   git config pull.rebase false  # Merge
Hinweis:   git config pull.rebase true   # Rebase
Hinweis:   git config pull.ff only       # ausschließlich Vorspulen
`````
`````
git pull origin main

`````
4# go back to your branch
`````
git checkout v4
`````

5# merge from main

`````
git merge main
`````


