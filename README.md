# GIT Reference

--Run this command in the working directory you want to track:<br>
git init

--Run this command to save:<br>
git commit

--Run this to see status:<br>
git status

--Run this to add files to staging area:<br>
git add Filename.txt Filename.md filename.etc<br>
to add a file(s)<br>
or<br>
git add .<br>
to add all files<br>

--Check Status again:<br>
git status

--Add a comment to the commit:<br>
git commit -m "Initial Commit"

--Create repo in Github

This will give you the commands to type into the terminal such as:

git remote add origin git@github.com:chilldev-build/GIT.git<br>
git push -u origin master


To recap:<br>
git init<br>
git commit<br>
git status<br>
git add Filename.txt Filename.md filename.etc<br>
git status<br>
git commit -m "Initial Commit"<br>
git remote add origin git@github.com:chilldev-build/GIT.git<br>
git push -u origin master<br>

Commit after initial commit:<br>
git commit<br>
git status<br>
git add Filename.txt Filename.md filename.etc<br>
git status<br>
git commit -m "Add to readme.md file"<br>
git push<br>


# Fork and Pull

Go to repo in Github and fork it at the top right.<br>
Create a directory.<br>
Run the command in that directory:<br> 
git init<br>
Run the command:<br>
git remote add origin "Paste in the clone/download address here"<br>
Then run the command to pull the master branch or whatever branch you need:<br>
git pull origin master<br>
