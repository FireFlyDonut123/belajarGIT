# belajarGIT
Tugas-git
Tugas-html
Tugas-css
Tugas-js
Tugas-midProject
Tugas-php
Tugas-finalProject

Daftar perintah GIT
...
``` shell 
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git status
On branch Tugas-git
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-git.txt

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git add Tugas-git.txt
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git status
On branch Tugas-git
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-git.txt

PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git commit -m "Tugas Web H 1" 
[Tugas-git 4627df3] Tugas Web H 1
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git checkout main 
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git merge Tugas-git
Updating ea3a683..4627df3
Fast-forward
 Tugas-git.txt | 1 +
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 341 bytes | 56.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/FireFlyDonut123/belajarGIT.git
   ea3a683..4627df3  main -> main
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git branch "Tugas-html"
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git checkout "Tugas-html"
Switched to branch 'Tugas-html'
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git add "Tugas-html.txt"
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git status
On branch Tugas-html
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-html.txt

PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git commit -m "Tugas Web H 1.1"
[Tugas-html 169542f] Tugas Web H 1.1
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git merge Tugas-html
Updating 4627df3..169542f
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git branch Tugas-css
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git checkout "Tugas-css"
Switched to branch 'Tugas-css'
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git add "Tugas-css.txt"
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git status
On branch Tugas-css
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-css.txt

PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git commit -m "Tugas Web H 1.2"
[Tugas-css b76a117] Tugas Web H 1.2
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git checkout  main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git merge Tugas-css
Updating 169542f..b76a117
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git branch Tugas-js
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git checkout "Tugas-js"
Switched to branch 'Tugas-js'
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git add "Tugas-js.txt"
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git status
On branch Tugas-js
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-js.txt

PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git commit -m "Tugas Web H 1.3"
[Tugas-js ea65094] Tugas Web H 1.3
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git merge Tugas-js
Updating b76a117..ea65094
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git branch Tugas-midProject
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git checkout "Tugas-midProject"
Switched to branch 'Tugas-midProject'
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git status                
On branch Tugas-midProject
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-midProject.txt

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git add "Tugas-midProject.txt"
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git status
On branch Tugas-midProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-midProject.txt

PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git commit -m "Tugas Web H 1.4"
[Tugas-midProject 3cf6767] Tugas Web H 1.4
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 3 commits.
  (use "git push" to publish your local commits)
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git log 
commit ea65094a8ba3ea3bcf34403cef0e127496e69e2f (HEAD -> main, Tugas-js)
Author: Billy Ambarura <billyambarura026@sttudent.unsrat.ac.id>
Date:   Mon Mar 11 10:55:03 2024 +0800

    Tugas Web H 1.3

commit b76a11799526cca8dc8b0695764339d92fc8ebdf (Tugas-css)
Author: Billy Ambarura <billyambarura026@sttudent.unsrat.ac.id>
Date:   Mon Mar 11 10:49:25 2024 +0800

    Tugas Web H 1.2

commit 169542f4b2287dc54567cd0e7830aa341761cb3c (Tugas-html)
Author: Billy Ambarura <billyambarura026@sttudent.unsrat.ac.id>
Date:   Mon Mar 11 10:44:08 2024 +0800

    Tugas Web H 1.1

commit 4627df3a184de71d537d8fcf7b4c9674abaea5e3 (origin/main, origin/HEAD, Tugas-git)
Author: Billy Ambarura <billyambarura026@sttudent.unsrat.ac.id>
Date:   Mon Mar 11 10:34:29 2024 +0800

    Tugas Web H 1

commit ea3a683453921d76546d2543898cf47981515af4
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git push 169542f4b2287dc54567cd0e7830aa341761cb3c
fatal: '169542f4b2287dc54567cd0e7830aa341761cb3c' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> 
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git push 
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 12 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (9/9), 841 bytes | 76.00 KiB/s, done.
Total 9 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), done.
To https://github.com/FireFlyDonut123/belajarGIT.git
   4627df3..ea65094  main -> main
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git merge Tugas-midProject
Updating ea65094..3cf6767
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 304 bytes | 76.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/FireFlyDonut123/belajarGIT.git
   ea65094..3cf6767  main -> main
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git branch Tugas-php
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git checkout "Tugas-php"
Switched to branch 'Tugas-php'
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git status
On branch Tugas-php
nothing to commit, working tree clean
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git add "Tugas-php.txt"
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git status
On branch Tugas-php
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-php.txt

PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git commit -m "Tugas Web H 1.5"
[Tugas-php 2bcb6f1] Tugas Web H 1.5
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git merge "Tugas-php"
Updating 3cf6767..2bcb6f1
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 304 bytes | 60.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/FireFlyDonut123/belajarGIT.git
   3cf6767..2bcb6f1  main -> main
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git branch Tugas-finalProject
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git checkout "Tugas-finalProject"
Switched to branch 'Tugas-finalProject'
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git status
On branch Tugas-finalProject
nothing to commit, working tree clean
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git add "Tugas-finalProject.txt"
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git status
On branch Tugas-finalProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-finalProject.txt

PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git status
On branch Tugas-finalProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-finalProject.txt

PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git commit -m "Tugas Web H 1.6"
[Tugas-finalProject 4b92aed] Tugas Web H 1.6
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git merge "Tugas-finalProject"
Updating 2bcb6f1..4b92aed
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 306 bytes | 102.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/FireFlyDonut123/belajarGIT.git
   2bcb6f1..4b92aed  main -> main
PS C:\Users\HP\OneDrive\Documents\Tugas WEB H\belajarGIT> 
```