# courses
Submissions for courses  

###Setting up Git Bash  
  
*On Git Bash (once):*  
git config --global user.name "NJBongithub"
git config --global user.email "NJBongithub@gmail.com"  
git config --list  
exit  
  
###Linking a local folder to GitHub repo  
  
*On Git Bash (once):*  
mkdir ~/datasciencecoursera  
cd ~/datasciencecoursera  
git init  
git remote set-url --add origin https://github.com/NJBongithub/courses.git  

also maybe if repo is new
git push -u origin master

###Sync'ing changes as you go  
  
*On Git Bash (as needed):*  
cd ~/datasciencecoursera  
git add -A  
git commit -m "message must be entered"  
git pull  
git push  

###Branch  
  
git checkput -b branchname     this creates a branch  
git branch     this switches into it  
git checkout master     this switches back to master  
