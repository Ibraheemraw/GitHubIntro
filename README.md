Git Introduction and Terminal Introduction


Career Prep for iOS 

Last login: Fri Oct  5 10:14:21 on ttys011
Pursuits-MacBook-Pro-3:~ ibraheem.r$ ls
Applications    Documents    Library        Music        Public
Desktop        Downloads    Movies        Pictures
Pursuits-MacBook-Pro-3:~ ibraheem.r$ cd ~ /documents 
Pursuits-MacBook-Pro-3:~ ibraheem.r$ cd ~ /Documents/ 
Pursuits-MacBook-Pro-3:~ ibraheem.r$ ls
Applications    Documents    Library        Music        Public
Desktop        Downloads    Movies        Pictures
Pursuits-MacBook-Pro-3:~ ibraheem.r$ cd ~/Documents/ 
Pursuits-MacBook-Pro-3:Documents ibraheem.r$ ls
Pursuits-MacBook-Pro-3:Documents ibraheem.r$ pwd
/Users/ibraheem.r/Documents
Pursuits-MacBook-Pro-3:Documents ibraheem.r$ mkdir GitIntro 
Pursuits-MacBook-Pro-3:Documents ibraheem.r$ ls
GitIntro
Pursuits-MacBook-Pro-3:Documents ibraheem.r$ cd GitIntro
Pursuits-MacBook-Pro-3:GitIntro ibraheem.r$ ls
Pursuits-MacBook-Pro-3:GitIntro ibraheem.r$ echo "Git Introduction and Terminal Introduction" >> README.md
Pursuits-MacBook-Pro-3:GitIntro ibraheem.r$ ls
README.md
Pursuits-MacBook-Pro-3:GitIntro ibraheem.r$ open README.md 
Pursuits-MacBook-Pro-3:GitIntro ibraheem.r$ git init 
Initialized empty Git repository in /Users/ibraheem.r/Documents/GitIntro/.git/
Pursuits-MacBook-Pro-3:GitIntro ibraheem.r$ ls
README.md
Pursuits-MacBook-Pro-3:GitIntro ibraheem.r$ ls -a
.        ..        .git        README.md
Pursuits-MacBook-Pro-3:GitIntro ibraheem.r$ ls
README.md
Pursuits-MacBook-Pro-3:GitIntro ibraheem.r$ git status 
On branch master

No commits yet

Untracked files:
(use "git add <file>..." to include in what will be committed)

README.md

nothing added to commit but untracked files present (use "git add" to track)
Pursuits-MacBook-Pro-3:GitIntro ibraheem.r$ git add README.md
Pursuits-MacBook-Pro-3:GitIntro ibraheem.r$ git status 
On branch master

No commits yet

Changes to be committed:
(use "git rm --cached <file>..." to unstage)

new file:   README.md

Pursuits-MacBook-Pro-3:GitIntro ibraheem.r$ touch temp.txt
Pursuits-MacBook-Pro-3:GitIntro ibraheem.r$ ls
README.md    temp.txt
Pursuits-MacBook-Pro-3:GitIntro ibraheem.r$ rm -rf temp.txt 
Pursuits-MacBook-Pro-3:GitIntro ibraheem.r$ ls
README.md
Pursuits-MacBook-Pro-3:GitIntro ibraheem.r$ open README.md 
