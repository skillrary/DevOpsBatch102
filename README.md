# DevOpsBatch102
git --version
git init
git status
git add
git commit
git rm --cached
git log
git config --global user.email "mithun@skillrary.com"
git config --global user.name "Mithun Ashok"
git restore a.txt
git add b.txt c.txt d.txt
git restore --staged b.txt c.txt d.txt

git add .
git restore --staged .
git add *.txt
git add b*.txt
git commit -m "Added b.txt"
git commit -a -m "Added 3rd line to a.txt"
git checkout master
git log --oneline
git log -p
git show
git status -s



git --version -- Shows the version of git

git init -- Initiate a repository

git status -- Shows current git status

git add -- Stages a file

git commit -- Commits staged file to local repository

git rm --cached -- Removes a staged file 

git log -- Displays commit logs

git config --global user.email "mithun@skillrary.com" -- Adding user/owner email to local repository

git config --global user.name "Mithun Ashok" -- Adding user/owner name

git restore a.txt -- Restoring file status

git add b.txt c.txt d.txt -- Adding multiple files

git restore --staged b.txt c.txt d.txt -- Restoring multiple files from staging area

git add . -- Adding all the files

git restore --staged . -- Restoring all the files from staging

git add *.txt -- Add all the files to stating matching wild card character *

git add b*.txt -- Adding all the files to staging starting with b and ending with txt

git commit -m "Added b.txt" -- Commiting with a message

git commit -a -m "Added 3rd line to a.txt" -- Adding a file to stating and commiting with a single command

git checkout master -- Moving around with different branches or commit id's

git log --oneline -- Show short version of log

git log -p -- Show extensive logging

git show -- Git show to show the details of each commit id

git status -s -- Shorter version of status


git tag Release3.0


6th Nov 2019
git tag -a -m "Decided to tag the name" Release2.1  -- Create a tag with an annotation
git tag -m "Decided to tag the name" Release2.1 -- Create a tag with an annotation
git tag -n -- List all tags with messages
git tag --list  -- List the names of tag
git tag -d Release3.0 - Delete a tag
git branch PRBug1.0 -- Create a Branch
git branch -- List all the Branches
git checkout PRBug1.0 -- Move to a Branch
git log --oneline --all -- Display all the logs including all the branches
git log --all --oneline --graph -- Display all logs with a graph
git merge PRBug1.0 -- Merge PRBug1.0 to Master Branch. Remember to be on Master before executing this command

7th Nov 2019

8th Nov 2019
git config --global core.autocrlf true
git merge 


13th Nov 2019
git clone https://github.com/MythMithun/devops102batch.git  -- Clone a remote repository to local using http url
git push origin -- Push local updates to remote repository
git pull origin -- Pull latested updates from remote repository
git remote -- List down remote repository names
git remote -v -- List down remote repository names along with url. -v stands for verbose.
git fetch origin -- Fetching latest details from remote is like doing a sync betwee 2 repositories without a commit
git remote add remote1 https://github.com/MythMithun/emptyrepo.git  -- Adding a new remote repository
git push -u remote1 master -- Pusing updates to a newly created repository

14th Nov 2019


15th Nov 2019
git remote rm remote1
