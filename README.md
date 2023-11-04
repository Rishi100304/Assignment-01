# Assignment-01
-git init //Initialising the git file in local repository
-notepad sample.txt //Creating a text file sample.txt

sample.txt:
Hi Mam!
This is sample text file

-git add . //Adding the sample.text file to the staging area
-git commit -m "First commit on sample file" //Committing sample.txt file to the local repository
-git remote add origin master "https://github.com/Rishi100304/Assignment-01.git" //Creates the connection between the github repository and local repository"
-git push origin master // Push the sample.txt file from local repository to remote repository in the master branch

-git branch feature-branch //Creating the feature branch
-git checkout feature-branch //Switching from Master branch to feature branch
-notepad sample.txt //Making changes in the sample text file 

sample.text:
Hi Mam!
This is sample text file
This is change made in sample text file

-git add . //Adding the updated sample text file in the feature bramch
-git commit -m "Second commit on sample file" //Committing the sample text file to the local repository for the second time
-git push origin feature-branch //pushing the updated sample.txt file from local repository to remote repository in the feature branch

-git checkout master //Switching from feature branch to master branch
-git merge feature-branch //Merging the master branch and feature-branch
-git push origin master //pushing the file in merged master branch and feature-branch from locak repository to remote repository
