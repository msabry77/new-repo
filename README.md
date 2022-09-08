
*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

ssh key and merg it to github account


clone 

git clone "link on github "

cd to the folder 

git status 
git add . to add al changes


commit 

git commit -m "add the message " to save it localy in your machine

push

git push origin master or git show-ref

in user name you type user name but in password you must type the token 

pull

*******************************

to add from local machine after creating folder  

git init 

the git add (name of the file ) or git add .


# this error 
{
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists. 
}

to solve it you must make an empty reposotry in github

then 
git remote add origin (then past the link)

to check if its done 

git remote -v


************************************************************

git branch (to see brances) 


git checkout -b (name of new branch)

git checkout (to switch between branches)


press tab to auto complete


if i modified the branche then i swithed to the master by checkingout the master ramin so i must merge to with each others

if you want to me

git diff (name of the branch )   it tellls you the different betwen the two files

git branch -d (name of the branch )  to delete the branch 

git reset (used to undo changes

git reset HEAD~1    (for undo commited - you can change the number after HEAD~ with the number of commiting operation you want to undo

git log (to show all of your logs)

to reset the commit 
git reset *the id of commit*

to reset the commit and every changes you made in the editor
git reset --hard *the id of commit oper*    


finnaly fork button it maske easy access of others repo 

