# git-github-tutorial
The full tutorial notes for Git &amp; GitHub 
WHAT IS GIT?
1. Git is a version control system. it is very popular and free to use to users and it is used for small as well as large projects.
2. It is mainly used to track the history of the written codes and programs.
3. It also helps in the collaboration of the team work for a given project.

WHAT IS GITHUB?
1. GitHub is a website which allow us to make changes and allow to run our program or we can say it manages the codes.
2. We create folders called as repository(repos) in the GitHub for the storage of the codes by the developers.

HOW TO USE GITHUB?
1. Firstly we have to create an account in GitHub website .
2. create a repository for the read. me in the GitHub. 
3. COMMIT keyword is used to make any new changes in the repository stored in the GitHub.
 
@INSTALL AND ESTABLISH GITBASH IN THE DESTOP 

CONFIGURE THE GIT 
1.It can be of two types:
  global
  local
2. It is used to connect the GitHub with our git with the preferred email which we had sign in the GitHub account.
3. By using "% git config --global user.name "my NAME".
4. git config --global user.email "someone @gamil.com".
5. git config --list.
6. Git has a credential helper which is used to maintain and manage the GitHub account and information.

BASIC COMMANDS OF GIT
1.CLONE
This command this used to make a copy of our command in our local system. we use http for accessing our code in the vs code .
by using "git clone " link"
 1.1 We use cd(change directory) for doing any changes in the folder or to enter in any folder . 
 1.2 We us ls to get the list of the files in the folder.
 1.3 We use ls -a to see the hidden files of any folders.
2. STATUS 
IT shows the current status of our repository . it also detects the changes occur in the vs code. 
 by using "git status"
As we do any modification in the vs code it shows in the terminal which is not detected by the GitHub. 
 FOUR TYPES OF GIT STATUS :
A. Untracked: Not able to tracked by the GitHub when we add any new file in the vs code.  
B. Modified: changes have been done by the user. 
C. Unmodified : Changes must not be done by the user.
D. Staged : File is ready to committed. 
Firstly we need to add new file in the repository to get to be staged in the folder the the file is ready to br committed in the GitHub. 

 ADD AND COMMIT 
 
ADD: Adding or changing new files into the directory to the staging area.
by using  ( git add "file name ")

COMMIT: It is the record of the changes'
by using ( git commit -m "some message ".

PUSH COMMAND 
It is used to upload the local vs code system repository changes to the GitHub remote repository.
by using (git push origin main)

INIT COMMAND 
It is used to create a new git repository in the GitHub. 
1. To came in the main repo  do the follows ;
      (cd ..)
2. To create a new repo in the vs code we need to do
      mkdir "name of the repo"
3. to came inside the repo we need to do;
      cd "name of the repo"
4. Enter in the repo and check its list by using the (ls -a)
  
THEREW ARE SOME COMMANDS USED IN THE INIT COMMAND ARE:
1. git init
2. git remote add origin "link"
3.git remote -v (to verify the remote)
4. git branch (to chack branch )
5. git branch -M main(to remane the branch )
6. git push origin main 

   -> WORFLOW :-
    
    GitHub repo-> Clone -> Changes -> Add -> Commit -> Push 
  
GIT BRANCHES :
1. git branch (to check branch )
2. git branch -M main (to rename branch )
3. git checkout <- branch name -> (to navigate )
4. git checkout -b  <- new branch name -> ( to create a new branch )
5. git branch -d <- to delete a branch )
TO show all this changes done on our GitHub repo we do " git push origin main" 

MERGE CODE 
 
1WAY :
            a) git diff <- branch name ->
               ( to compare, commit, branches, fileas and more )
             b) git merge <-branch name ->
                ( to merge 2 branches )
2 WAY :
             create PR (pull request)
PULL REQUEST: It is used by the multiple users to merge their different files or repo in the GitHub to connect diff branches altogether.

PULL COMMAND : It is used to make changes froma the remote GitHub repo to the local system repo. it fetch or download all the data from the remote repo and immediately update the local repository. 
RESOLVING MERGE CONFLICTS :  When different repos have same place difference then it creats an conflict to merge  then we use the resolving merge conflicts, we done some manual work on the basis of our preference in the repository. By the help of the vs code by the multiple option given by the system.
UNDOING CHANGES : 
case 1: git reset <-file name ->
            git reset 
case2: commit changes (for single commits )
           git reset head~1
case3: commited changes (for many commits )
           git reset<- commit hash-> 
           git reset --hard <- commit hash->  

GIT LOG keyword is used to show all the commits performed in the repo 
FORK: 
It is a new repo that shares code and visibility setting with the original repo. It is a kind of a rough copy.   give this notes into a proper form of cheetsheet or notes for attaching it to my github account repo
