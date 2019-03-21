# HowToUploadYourProjectToGithub
To Upload Your Folder Project To Github

1.  You must install git first https://git-scm.com/
2.  Open cmd or git bash and make sure path of your cmd or git bash in directory project/file you want to upload/push
3.  Git config --global user.name "username anda" 
4.  Git config --global user.email isi_dengan_email_anda@ymail.com 
5.  Git init 
6.  Git add * 
7.  Git commit –m "versi 1.0.0" 
8.  Git remote add origin yourRepository example (https://github.com/Three-A/HowToUploadYourProjectToGithub)
9.  Git pull origin master 
10. Git push origin master 


Android Studio to Github
1. Sign up and create a GitHub account in www.github.com.
2. Download git from https://git-scm.com/downloads and install it in your system.
3. Open the project in android studio and go to File -> Settings -> Version Control -> Git.
4. Click on test button to test "path to Git executables". If successful message is shown everything is ok, else navigate to git.exe from  where you installed git and test again.
5. Go to File -> Settings -> Version Control -> GitHub. Enter your email and password used to create GitHub account and click on OK button.
6. Then go to VCS -> Import into Version Control -> Share Project on GitHub. Enter Repository name, Description and click Share button.
7. In the next window check all files inorder to add files for initial commit and click OK.
8. Now the project will be uploaded to the GitHub repository and when uploading is finished we will get a message in android studio showing "Successfully shared project on GitHub". Click on the link provided in that message to go to GitHub repository.

To make commit in Android Studio
Go to VCS -> Git -> Commit file . Then type a commit message and click on commit button

Best Practice to branch and merge

---------------------------------
git branch namaBranch             //untuk membuat branch baru
---------------------------------

---------------------------------
git checkout namaBranch           //untuk pindah ke branch lain
---------------------------------

---------------------------------
git checkout -b myfeature develop //untuk pindah ke branch baru bernama myfeature
---------------------------------

---------------------------------
git merge --no-f namaBranch       //untuk merge dari branch yang sudah di develop
---------------------------------

---------------------------------
git push origin namaBranch        //setelah merge lalu di push
---------------------------------



