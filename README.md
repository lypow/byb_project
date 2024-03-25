
C:\Users\lydia>cd C:\Users\lydia>cd C:\Users\lydia\Documents\byb_project
The filename, directory name, or volume label syntax is incorrect.

C:\Users\lydia>cd byb_project
The system cannot find the path specified.

C:\Users\lydia>cd Documents

C:\Users\lydia\Documents>cd byb_project

C:\Users\lydia\Documents\byb_project>git init
Initialized empty Git repository in C:/Users/lydia/Documents/byb_project/.git/

C:\Users\lydia\Documents\byb_project>git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

C:\Users\lydia\Documents\byb_project>git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        helloWorld.py

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\lydia\Documents\byb_project>git add helloWorld.py

C:\Users\lydia\Documents\byb_project>git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   helloWorld.py


C:\Users\lydia\Documents\byb_project>git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   helloWorld.py

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   helloWorld.py


C:\Users\lydia\Documents\byb_project>git add helloWorld.py

C:\Users\lydia\Documents\byb_project>git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   helloWorld.py


C:\Users\lydia\Documents\byb_project>git commit -m
error: switch `m' requires a value

C:\Users\lydia\Documents\byb_project>git commit -m "Changed program to use helloWorld.py"
[master (root-commit) 115437f] Changed program to use helloWorld.py
 1 file changed, 1 insertion(+)
 create mode 100644 helloWorld.py

C:\Users\lydia\Documents\byb_project>git status
On branch master
nothing to commit, working tree clean

C:\Users\lydia\Documents\byb_project>git remote add helloWorld.py https://github.com/lypow/byb_project

C:\Users\lydia\Documents\byb_project>git push -u helloWorld.py master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 266 bytes | 66.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/lypow/byb_project
 * [new branch]      master -> master
branch 'master' set up to track 'helloWorld.py/master'.

C:\Users\lydia\Documents\byb_project>
