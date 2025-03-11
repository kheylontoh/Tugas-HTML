user@LAPTOP-NSB71ORR MINGW64 ~
$ cd "D:\FILE\Sem 6\Tugas PW\tugas website html\TIK2032-Project"

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project (main)
$ git clone https://github.com/kheylontoh/Tugas-HTML.git
Cloning into 'Tugas-HTML'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project (main)
$ cd HTML website
bash: cd: too many arguments

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project (main)
$ cd HTML-website
bash: cd: HTML-website: No such file or directory

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project (main)
$ cd htmlwebsite
bash: cd: htmlwebsite: No such file or directory

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project (main)
$ cd Tugas-HTML

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git checkout -b Tugas-HTML
Switched to a new branch 'Tugas-HTML'

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Tugas-HTML)
$ git touch Tugas-HTML.txt
git: 'touch' is not a git command. See 'git --help'.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Tugas-HTML)
$ touch Tugas-HTML.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Tugas-HTML)
$ git add Tugas-HTML.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Tugas-HTML)
$ git config --global user.name "kheylontoh"

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Tugas-HTML)
$ git config --global user.email "kherenlontoh026@student.unsrat.ac.id"

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Tugas-HTML)
$
git commit -m "Menambahkan Tugas-HTML.txt"
[Tugas-HTML 11961ca] Menambahkan Tugas-HTML.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-HTML.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Tugas-HTML)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ it merge Tugas-HTML
bash: it: command not found

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git merge Tugas-HTML
Updating 63e03a4..11961ca
Fast-forward
 Tugas-HTML.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-HTML.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 309 bytes | 103.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/kheylontoh/Tugas-HTML.git
   63e03a4..11961ca  main -> main

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git checkout -b Home
Switched to a new branch 'Home'

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Home)
$ touch Home.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Home)
$ git add Home.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Home)
$ git commit -m "Menambahkan Tugas-Html.txt"
[Home efa3f4a] Menambahkan Tugas-Html.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Home.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Home)
$ git commit -m "Menambahkan Home.txt"
On branch Home
nothing to commit, working tree clean

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Home)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git merge Home
Updating 11961ca..efa3f4a
Fast-forward
 Home.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Home.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 305 bytes | 152.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/kheylontoh/Tugas-HTML.git
   11961ca..efa3f4a  main -> main

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git checkout -b Gallery
Switched to a new branch 'Gallery'

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Gallery)
$ touch Gallery.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Gallery)
$ git add Galerry.txt
fatal: pathspec 'Galerry.txt' did not match any files

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Gallery)
$ git add Gallery.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Gallery)
$ git commit -m "Menambahkan Gallery.txt"
[Gallery 06e55e4] Menambahkan Gallery.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Gallery.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Gallery)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git merge Gallery
Updating efa3f4a..06e55e4
Fast-forward
 Gallery.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Gallery.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git push origin main

Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 259 bytes | 259.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/kheylontoh/Tugas-HTML.git
   efa3f4a..06e55e4  main -> main

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git checkout -b Blog
Switched to a new branch 'Blog'

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Blog)
$ touch Blog.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Blog)
$ git add Blog.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Blog)
$ git commit -m "Menambahkan Blog.txt"
[Blog bf01889] Menambahkan Blog.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Blog.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Blog)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git merge Blog
Updating 06e55e4..bf01889
Fast-forward
 Blog.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Blog.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 254 bytes | 254.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/kheylontoh/Tugas-HTML.git
   06e55e4..bf01889  main -> main

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git checkout -b Contact
Switched to a new branch 'Contact'

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Contact)
$ touch Contact.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Contact)
$ git add Contact.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Contact)
$ git commit -m "Menambahkan Contact.txt"
[Contact e4540c6] Menambahkan Contact.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Contact.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (Contact)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git merge Contact
Updating bf01889..e4540c6
Fast-forward
 Contact.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Contact.txt

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 253 bytes | 253.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/kheylontoh/Tugas-HTML.git
   bf01889..e4540c6  main -> main

user@LAPTOP-NSB71ORR MINGW64 /d/FILE/Sem 6/Tugas PW/tugas website html/TIK2032-Project/Tugas-HTML (main)
$ git push origin --all
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/kheylontoh/Tugas-HTML.git
 * [new branch]      Blog -> Blog
 * [new branch]      Contact -> Contact
 * [new branch]      Gallery -> Gallery
 * [new branch]      Home -> Home
 * [new branch]      Tugas-HTML -> Tugas-HTML
