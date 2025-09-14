win10@Gemao789 MINGW64 ~
$ cd Desktop

win10@Gemao789 MINGW64 ~/Desktop
$ mkdir Gemao_IT120_Act1
mkdir: cannot create directory ‘Gemao_IT120_Act1’: File exists

win10@Gemao789 MINGW64 ~/Desktop
$ cd Gemao_IT120_Act1

win10@Gemao789 MINGW64 ~/Desktop/Gemao_IT120_Act1 (master)
$ touch Profile.txt Education.txt Background.txt Readme.txt Test.py

win10@Gemao789 MINGW64 ~/Desktop/Gemao_IT120_Act1 (master)
$ git init
Reinitialized existing Git repository in C:/Users/win10/Desktop/Gemao_IT120_Act1
/.git/

win10@Gemao789 MINGW64 ~/Desktop/Gemao_IT120_Act1 (master)
$ git add .
warning: in the working copy of 'Background.txt', LF will be replaced by CRLF th
e next time Git touches it
warning: in the working copy of 'Education.txt', LF will be replaced by CRLF the
 next time Git touches it

win10@Gemao789 MINGW64 ~/Desktop/Gemao_IT120_Act1 (master)
$ git commit -m "Initial Commit"
[master 5e8f659] Initial Commit
 5 files changed, 17 insertions(+)
 rename Read.txt => Readme.txt (100%)

win10@Gemao789 MINGW64 ~/Desktop/Gemao_IT120_Act1 (master)
$ git branch Gemao_B1
fatal: a branch named 'Gemao_B1' already exists

win10@Gemao789 MINGW64 ~/Desktop/Gemao_IT120_Act1 (master)
$ git branch Gemao_B2
fatal: a branch named 'Gemao_B2' already exists

win10@Gemao789 MINGW64 ~/Desktop/Gemao_IT120_Act1 (master)
$ git branch Gemao_B3
fatal: a branch named 'Gemao_B3' already exists

win10@Gemao789 MINGW64 ~/Desktop/Gemao_IT120_Act1 (master)
$ git branch Gemao_B4
fatal: a branch named 'Gemao_B4' already exists

win10@Gemao789 MINGW64 ~/Desktop/Gemao_IT120_Act1 (master)
$ git branch
  Gemao_B1
  Gemao_B2
  Gemao_B3
  Gemao_B4
* master

win10@Gemao789 MINGW64 ~/Desktop/Gemao_IT120_Act1 (master)
$ git add .

win10@Gemao789 MINGW64 ~/Desktop/Gemao_IT120_Act1 (master)
$ git commit -m "Initial Commit"
On branch master
nothing to commit, working tree clean

win10@Gemao789 MINGW64 ~/Desktop/Gemao_IT120_Act1 (master)
$ git checkout Gemao_B1
Switched to branch 'Gemao_B1'

win10@Gemao789 MINGW64 ~/Desktop/Gemao_IT120_Act1 (Gemao_B1)
$ git status
On branch Gemao_B1
nothing to commit, working tree clean

win10@Gemao789 MINGW64 ~/Desktop/Gemao_IT120_Act1 (Gemao_B1)
$ git merge master
Updating 4a0b945..5e8f659
Fast-forward
 Background.txt         | 1 +
 Education.txt          | 6 ++++++
 Profile.txt            | 7 +++++++
 Read.txt => Readme.txt | 0
 Test.py                | 3 +++
 5 files changed, 17 insertions(+)
 rename Read.txt => Readme.txt (100%)

win10@Gemao789 MINGW64 ~/Desktop/Gemao_IT120_Act1 (Gemao_B1)
$ .git add profile.txt
bash: .git: command not found

win10@Gemao789 MINGW64 ~/Desktop/Gemao_IT120_Act1 (Gemao_B1)
$ git add Profile.txt

win10@Gemao789 MINGW64 ~/Desktop/Gemao_IT120_Act1 (Gemao_B1)
$ git add Readme.txt

win10@Gemao789 MINGW64 ~/Desktop/Gemao_IT120_Act1 (Gemao_B1)
$ git commit -m "New insertion in this file"
On branch Gemao_B1
nothing to commit, working tree clean

win10@Gemao789 MINGW64 ~/Desktop/Gemao_IT120_Act1 (Gemao_B1)
$ git checkout Gemao_B2
Switched to branch 'Gemao_B2'
