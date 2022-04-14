1 - https://github.com/DaviNoronhaAlmeida/my_first_steps

2 - Davi@DESKTOP-NMI4QUF MINGW64 ~/OneDrive/Área de Trabalho/my_first_steps (master)
$ git init
Reinitialized existing Git repository in C:/Users/narut/OneDrive/Área de Trabalho/my_first_steps/.git/

Davi@DESKTOP-NMI4QUF MINGW64 ~/OneDrive/Área de Trabalho/my_first_steps (master)
$ git add .

Davi@DESKTOP-NMI4QUF MINGW64 ~/OneDrive/Área de Trabalho/my_first_steps (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   Novo Documento de Texto.txt


Davi@DESKTOP-NMI4QUF MINGW64 ~/OneDrive/Área de Trabalho/my_first_steps (master)
$ git commit -m "first commit"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Davi@DESKTOP-NMI4QUF.(none)')

Davi@DESKTOP-NMI4QUF MINGW64 ~/OneDrive/Área de Trabalho/my_first_steps (master)
$ git config --global user.email "davinoronhaalmeida@gmail.com"

Davi@DESKTOP-NMI4QUF MINGW64 ~/OneDrive/Área de Trabalho/my_first_steps (master)
$ git config --global user.name "Davi"

Davi@DESKTOP-NMI4QUF MINGW64 ~/OneDrive/Área de Trabalho/my_first_steps (master)
$ git commit -m "first commit"
[master (root-commit) 245de72] first commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Novo Documento de Texto.txt

Davi@DESKTOP-NMI4QUF MINGW64 ~/OneDrive/Área de Trabalho/my_first_steps (master)
$ git branch -M main

Davi@DESKTOP-NMI4QUF MINGW64 ~/OneDrive/Área de Trabalho/my_first_steps (main)
$ git remote add origin https://github.com/DaviNoronhaAlmeida/my_first_steps.git

Davi@DESKTOP-NMI4QUF MINGW64 ~/OneDrive/Área de Trabalho/my_first_steps (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 232 bytes | 232.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/DaviNoronhaAlmeida/my_first_steps.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

3 - Davi@DESKTOP-NMI4QUF MINGW64 ~/OneDrive/Área de Trabalho/my_first_steps (main)
$ git add .

Davi@DESKTOP-NMI4QUF MINGW64 ~/OneDrive/Área de Trabalho/my_first_steps (main)
$ git commit -m "Mudança"
[main da3c0a7] Mudança
 2 files changed, 1 insertion(+)
 delete mode 100644 Novo Documento de Texto.txt
 create mode 100644 "ol\303\241_mundo.txt"

Davi@DESKTOP-NMI4QUF MINGW64 ~/OneDrive/Área de Trabalho/my_first_steps (main)
$ git push -u origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (1/1), done.
Writing objects: 100% (3/3), 261 bytes | 261.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/DaviNoronhaAlmeida/my_first_steps.git
   245de72..da3c0a7  main -> main
branch 'main' set up to track 'origin/main'.

4 - Serei_ignorado.txt