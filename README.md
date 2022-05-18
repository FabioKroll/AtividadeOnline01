# AtividadeOnline01
Atividade Online 01 do curso Programador FullStack

Foi feita uma alteração no arquivo versoes.txt, inserindo a palavra "Praticando".

A sequência de códigos foi a seguinte:


Fábio Kroll de Lima@DESKTOP-3EQ6VFU MINGW64 ~/Desktop/Programador Full-Stack/2 - Introdutório/2 - Versionamento/Atividade 01
$ git init
Initialized empty Git repository in C:/Users/Fábio Kroll de Lima/Desktop/Programador Full-Stack/2 - Introdutório/2 - Versionamento/Atividade 01/.git/

Fábio Kroll de Lima@DESKTOP-3EQ6VFU MINGW64 ~/Desktop/Programador Full-Stack/2 - Introdutório/2 - Versionamento/Atividade 01 (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        versoes.txt

nothing added to commit but untracked files present (use "git add" to track)

Fábio Kroll de Lima@DESKTOP-3EQ6VFU MINGW64 ~/Desktop/Programador Full-Stack/2 - Introdutório/2 - Versionamento/Atividade 01 (master)
$ git add versoes.txt

Fábio Kroll de Lima@DESKTOP-3EQ6VFU MINGW64 ~/Desktop/Programador Full-Stack/2 - Introdutório/2 - Versionamento/Atividade 01 (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   versoes.txt


Fábio Kroll de Lima@DESKTOP-3EQ6VFU MINGW64 ~/Desktop/Programador Full-Stack/2 - Introdutório/2 - Versionamento/Atividade 01 (master)
$ git commit -m "meu primeiro commit"
[master (root-commit) 6b63404] meu primeiro commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 versoes.txt

Fábio Kroll de Lima@DESKTOP-3EQ6VFU MINGW64 ~/Desktop/Programador Full-Stack/2 - Introdutório/2 - Versionamento/Atividade 01 (master)
$ git log
commit 6b63404e312fb339f216258da22d71075ee25a15 (HEAD -> master)
Author: Fábio de Lima <famil88@gmail.com>
Date:   Wed May 18 18:25:03 2022 -0300

    meu primeiro commit

Fábio Kroll de Lima@DESKTOP-3EQ6VFU MINGW64 ~/Desktop/Programador Full-Stack/2 - Introdutório/2 - Versionamento/Atividade 01 (master)
$ git remote add origin https://github.com/FabioKroll/AtividadeOnline01.git

Fábio Kroll de Lima@DESKTOP-3EQ6VFU MINGW64 ~/Desktop/Programador Full-Stack/2 - Introdutório/2 - Versionamento/Atividade 01 (master)
$ git remote -v
origin  https://github.com/FabioKroll/AtividadeOnline01.git (fetch)
origin  https://github.com/FabioKroll/AtividadeOnline01.git (push)

Fábio Kroll de Lima@DESKTOP-3EQ6VFU MINGW64 ~/Desktop/Programador Full-Stack/2 - Introdutório/2 - Versionamento/Atividade 01 (master)
$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 223 bytes | 223.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/FabioKroll/AtividadeOnline01.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.
[versoes.txt](https://github.com/FabioKroll/AtividadeOnline01/files/8721074/versoes.txt)

Fábio Kroll de Lima@DESKTOP-3EQ6VFU MINGW64 ~/Desktop/Programador Full-Stack/2 - Introdutório/2 - Versionamento/Atividade 01 (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   versoes.txt

no changes added to commit (use "git add" and/or "git commit -a")

Fábio Kroll de Lima@DESKTOP-3EQ6VFU MINGW64 ~/Desktop/Programador Full-Stack/2 - Introdutório/2 - Versionamento/Atividade 01 (master)
$ git add versoes.txt

Fábio Kroll de Lima@DESKTOP-3EQ6VFU MINGW64 ~/Desktop/Programador Full-Stack/2 - Introdutório/2 - Versionamento/Atividade 01 (master)
$ git commit -m "meu segundo commit"
[master 212f1b6] meu segundo commit
 1 file changed, 1 insertion(+)

Fábio Kroll de Lima@DESKTOP-3EQ6VFU MINGW64 ~/Desktop/Programador Full-Stack/2 - Introdutório/2 - Versionamento/Atividade 01 (master)
$ git push -u origin master
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 262 bytes | 262.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/FabioKroll/AtividadeOnline01.git
   6b63404..212f1b6  master -> master
branch 'master' set up to track 'origin/master'.

Fábio Kroll de Lima@DESKTOP-3EQ6VFU MINGW64 ~/Desktop/Programador Full-Stack/2 - Introdutório/2 - Versionamento/Atividade 01 (master)
$
