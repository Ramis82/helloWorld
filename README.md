# helloWorld
Cambio 1

Last login: Tue Nov  5 17:31:12 on ttys000
PikaPika:~ qa$ git --version
git version 2.23.0
PikaPika:~ qa$ cd ..
PikaPika:Users qa$ cd desktop
-bash: cd: desktop: No such file or directory
PikaPika:Users qa$ ls
Shared	admin	qa
PikaPika:Users qa$ cd qa
PikaPika:~ qa$ cd desktop
PikaPika:desktop qa$ cd github
PikaPika:github qa$ echo "# helloWorld" >> README.md
PikaPika:github qa$ git init
Initialized empty Git repository in /Users/qa/Desktop/github/.git/
PikaPika:github qa$ git add README.md
PikaPika:github qa$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   README.md

PikaPika:github qa$ git commit -m "first commit"
[master (root-commit) ae4be1f] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
PikaPika:github qa$ git remote add origin https://github.com/Ramis82/helloWorld.git
PikaPika:github qa$ git push -u origin master
Username for 'https://github.com': Ramis82
Password for 'https://Ramis82@github.com': 
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 223 bytes | 223.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/Ramis82/helloWorld.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
PikaPika:github qa$ git add README.md
PikaPika:github qa$ git commit -m "second commit"
[master 60fec42] second commit
 1 file changed, 1 insertion(+)
PikaPika:github qa$ git push -u origin master
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 263 bytes | 263.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/Ramis82/helloWorld.git
   ae4be1f..60fec42  master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
PikaPika:github qa$ 
