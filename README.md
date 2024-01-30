# my-website
first project in aptech

std@SFC-LAB201-PC16 MINGW64 ~/Desktop
$ git version
git version 2.43.0.windows.1

std@SFC-LAB201-PC16 MINGW64 ~/Desktop
$ mkdir hello

std@SFC-LAB201-PC16 MINGW64 ~/Desktop
$ cd hello

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello
$ git init
Initialized empty Git repository in C:/Users/STD/Desktop/hello/.git/

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ touch index.html

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ touch about.html

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        about.html
        index.html

nothing added to commit but untracked files present (use "git add" to track)

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ code .

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git add-A
git: 'add-A' is not a git command. See 'git --help'.

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ sit status
bash: sit: command not found

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git checkout
fatal: You are on a branch yet to be born

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        about.html
        index.html

nothing added to commit but untracked files present (use "git add" to track)

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git init index.html
fatal: cannot mkdir index.html: File exists

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git add-A
git: 'add-A' is not a git command. See 'git --help'.

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git checkout
fatal: You are on a branch yet to be born

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git checkout inex.html
error: pathspec 'inex.html' did not match any file(s) known to git

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git checkout index.html
error: pathspec 'index.html' did not match any file(s) known to git

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git add-A
git: 'add-A' is not a git command. See 'git --help'.

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git index.html add-A
git: 'index.html' is not a git command. See 'git --help'.

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git about.html add-A
git: 'about.html' is not a git command. See 'git --help'.

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        about.html
        index.html

nothing added to commit but untracked files present (use "git add" to track)

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git add-A
git: 'add-A' is not a git command. See 'git --help'.

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git add -A

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   about.html
        new file:   index.html


std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git commit -m "my final work"
[master (root-commit) 2ec5384] my final work
 2 files changed, 11 insertions(+)
 create mode 100644 about.html
 create mode 100644 index.html

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git log
commit 2ec53845d4201686da480e43a3a6ce90ed628538 (HEAD -> master)
Author: alishba56@gmail.com <alishba45@gmail.com>
Date:   Mon Jan 29 22:46:58 2024 -0800

    my final work

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git init
Reinitialized existing Git repository in C:/Users/STD/Desktop/hello/.git/

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git log
commit 2ec53845d4201686da480e43a3a6ce90ed628538 (HEAD -> master)
Author: alishba56@gmail.com <alishba45@gmail.com>
Date:   Mon Jan 29 22:46:58 2024 -0800

    my final work

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git code
git: 'code' is not a git command. See 'git --help'.

The most similar command is
        clone

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ code.
bash: code.: command not found

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ .code
bash: .code: command not found

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git .code
git: '.code' is not a git command. See 'git --help'.

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git config --global user.name "wasay khan"

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git config --global user.email "awasay624@gmail.com"

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git log
commit 2ec53845d4201686da480e43a3a6ce90ed628538 (HEAD -> master)
Author: alishba56@gmail.com <alishba45@gmail.com>
Date:   Mon Jan 29 22:46:58 2024 -0800

    my final work

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        my-website/

nothing added to commit but untracked files present (use "git add" to track)

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git add -A
error: 'my-website/' does not have a commit checked out
fatal: adding files failed

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        my-website/

nothing added to commit but untracked files present (use "git add" to track)

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git website add -A
git: 'website' is not a git command. See 'git --help'.

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        my-website/

nothing added to commit but untracked files present (use "git add" to track)

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git add -A
error: 'my-website/' does not have a commit checked out
fatal: adding files failed

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git checkout

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git add -A
error: 'my-website/' does not have a commit checked out
fatal: adding files failed

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        my-website/

nothing added to commit but untracked files present (use "git add" to track)

std@SFC-LAB201-PC16 MINGW64 ~/Desktop/hello (master)
$
