user@LAPTOP-NSB71ORR MINGW64 ~
$ cd "D:\FILE\Sem 6\Tugas PW\tugas website html\TIK2032-Project"

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project (main)
$ git clone https://github.com/kheylontoh/Tugas-HTML.git
fatal: destination path 'Tugas-HTML' already exists and is not an empty directory.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project (main)
$ git clone https://github.com/kheylontoh/Tugas-HTML.git
fatal: destination path 'Tugas-HTML' already exists and is not an empty directory.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project (main)
$ cd Tugas-HTML

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git checkout -b Tugas-HTML
fatal: a branch named 'Tugas-HTML' already exists

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git touch Tugas-HTML.txt
git: 'touch' is not a git command. See 'git --help'.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ touch Tugas-HTML.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git add Tugas-HTML.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git config --global user.name "kheylontoh"

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git config --global user.email "kherenlontoh026@student.unsrat.ac.id"

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git commit -m "Menambahkan Tugas-HTML.txt"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git chechout main
git: 'chechout' is not a git command. See 'git --help'.

The most similar command is
        checkout

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git checkout main
Already on 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git merge Tugas-HTML
Already up to date.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git push origin main
To https://github.com/kheylontoh/Tugas-HTML.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/kheylontoh/Tugas-HTML.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git checkout -b Home
fatal: a branch named 'Home' already exists

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git checkout -b home
fatal: a branch named 'home' already exists

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-H
$ git push origin --all
Enumerating objects: 14, done.
Counting objects: 100% (14/14), done.
Delta compression using up to 8 threads
Compressing objects: 100% (12/12), done.
Writing objects: 100% (14/14), 2.05 KiB | 420.00 KiB/s, done.
Total 14 (delta 3), reused 3 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), done.
To https://github.com/kheylontoh/Tugas-HTML.git
 * [new branch]      Blog -> Blog
 * [new branch]      Contact -> Contact
 * [new branch]      Gallery -> Gallery
 * [new branch]      Home -> Home
 * [new branch]      Tugas-HTML -> Tugas-HTML
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/kheylontoh/Tugas-HTML.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-H
$ git push origin --all
Everything up-to-date

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-H
$ git checkout -b Home
Switched to a new branch 'Home'

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-H
$ touch Tugas-Home.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-H
$ git add Home.txt
fatal: pathspec 'Home.txt' did not match any files

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-H
$ git checkout -b Home
fatal: a branch named 'Home' already exists

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Home)
$ touch Home.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Home)
$ git add Home.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Home)
$ git commit -m "Menambahkan Home.txt"
[Home e4d380d] Menambahkan Home.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-HTML/Home.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Home)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git merge Home
Updating 4018f40..e4d380d
Fast-forward
 Tugas-HTML/Home.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-HTML/Home.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 346 bytes | 346.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/kheylontoh/TIK2032-Project.git
   4018f40..e4d380d  main -> main

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git checkout -b Gallery
Switched to a new branch 'Gallery'

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Gallery)
$ touch Gallery.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Gallery)
$ git add Gallery.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Gallery)
$ git commit -m "Menambahkan Gallery.txt"
[Gallery fdbbe25] Menambahkan Gallery.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-HTML/Gallery.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Gallery)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git merge Gallery
Updating e4d380d..fdbbe25
Fast-forward
 Tugas-HTML/Gallery.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-HTML/Gallery.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 352 bytes | 352.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/kheylontoh/TIK2032-Project.git
   e4d380d..fdbbe25  main -> main

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git checkout -b Blog
Switched to a new branch 'Blog'

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Blog)
$ touch Blog.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Blog)
$ git add Blog.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Blog)
$ git commit -m "Menambahkan Blog.txt"
[Blog 59fc098] Menambahkan Blog.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-HTML/Blog.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Blog)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git merge Blog
Updating fdbbe25..59fc098
Fast-forward
 Tugas-HTML/Blog.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-HTML/Blog.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 356 bytes | 356.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/kheylontoh/TIK2032-Project.git
   fdbbe25..59fc098  main -> main

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git checkout -b Contact
Switched to a new branch 'Contact'

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Contact)
$ touch Contact.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Contact)
$ git add Contact.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Contact)
$ git commit -m "Menambahkan Contact.txt"
[Contact ef83e1b] Menambahkan Contact.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-HTML/Contact.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Contact)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git merge Contact
Updating 59fc098..ef83e1b
Fast-forward
 Tugas-HTML/Contact.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-HTML/Contact.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 338 bytes | 338.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/kheylontoh/TIK2032-Project.git
   59fc098..ef83e1b  main -> main

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git push origin --all
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/kheylontoh/TIK2032-Project.git
 * [new branch]      Blog -> Blog
 * [new branch]      Contact -> Contact
 * [new branch]      Gallery -> Gallery
 * [new branch]      Home -> Home

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$
