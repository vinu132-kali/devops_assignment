# devops_assignment

Steps:

1)First type "cd" command and then add your folder path and then initialize the git using "git init" 

2)Add a text file using "notepad sample.txt" & "git add sample.txt" command and then commit it using :- git commit -m "add comment here",to view commit you can use the command "git log" to view

3)git remote add origin "github repository path" this command is use to connect local to remote repository

4)To push we use "git push origin master"

5)Create new branch using "git branch feature" command, here feature is the name given to the new branch

6)After that shift the branch from master to feature, we use "git checkout feature"

7)After switching add some content to file which was created earlier and then commit, push it to feature branch

8)Now switching it back to master branch we use "git checkout master"

9)Then we merge feature and master branch, we use the follwing commands: a)git merge master b)git merge feature

10)And push it by typing "git push origin master"
