# Instructions for working with GIT

![](https://fuzeservers.ru/wp-content/uploads/3/0/c/30c29ce4cc08523ecc6e1f205bc207d0.jpeg)

>## Basic GIT commands:


## 1. *User registration:*

1. *git config --* - **git config --global user.name «Your name»**

2. *git config --global user.email example@example.com* - **input email**

## 2. *Other commands:*

* *git --version* - **Git System Version**

* *git init* - **Initialization of local repositorium**

* *git status* - **Output of the system status at the moment**

* *git add* - **Add file version**

* *git commit -m* **Add file to commit**

* *git diff* - **view changes in two branches**

* *git log* - **Output commitments in chronological order**

* *git checkout < Hash number of commitment or master >* - **Switching between different commitments**

## 3. *Auxiliary programs:*

* *git branch -d < branch name >*  **Delete branch by name**

* *git help* **Tips git commands**

## *Commands sequence:*

*git status-> git add... -> git status -> git commit -m "..."* 

>## <span style="color:red"> *Unrecommended commands for novice/begginer:*</span>
* *git pull* - **Adds any commitments to the branch automatically**

* *git fetch* - **Collects all commitments from the target branch that are not in the current branch and stores them in the local repository (it doesn't add to master branch)**

* *git merge < merged brunch >* - **Merges changes from the transferred branch into the current one**

> *For more information, see the* [Git documentation](https://git-scm.com/doc)