# aws-git-webapp
This is my web application 


Launch EC2 instance from AWS - with SSH access
Login to EC2 instance

Git commands
git clone                                --> clone project from remote repo to local repo

git add <filename>                       --> Working copy to staging copy
  
git commit -m “<commit-message>”         --> staging copy to local copy
  
git push                                 --> local copy to remote repo
  
git clone https://github.com/ssatya21/aws-git-webapp.git
git add index.html
  
git commit -m "Create index page" index.html
  
git push 
  
Generate a new token from developer settings from github user profile page (one time activity). Save the token and provide this when prompted while git push
  
git status                --> status of the files
  
git log                   --> shows all the commits with commit id, author, date and commit message
  
git log --oneline         --> logs all the commits in one line
  
git show <commit-id>      --> diff between current and previous commit
  
  
git config --global user.email <email-id>
  
git config --global user.name <username>
  
git config --global color.ui true

git reset HEAD <file> --> to unstage the file
  
  git pull --> pull the code commits from remote repo to local
