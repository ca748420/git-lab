Answer 1: git version 2.35.1.windows.1

Answer 2:
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager-core
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
core.editor="C:\Users\Cameron\AppData\Local\Programs\Microsoft VS Code\bin\code" --wait
user.email=ca748420@ohio.edu
user.name=Cameron Adler

Answer 3: A list of common and useful commands appears

Answer 4:
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        answers.md

nothing added to commit but untracked files present (use "git add" to track)

Answer 5:
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md

Answer 6:
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md

Answer 7:
[master (root-commit) 6cad4b8] Initial commit
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
 create mode 100644 answers.md
PS C:\Users\Cameron\Desktop\Summer2022\CS2400\git-lab> git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working dire
        modified:   answers.md

no changes added to commit (use "git add" and/or "git commit -a")

Answer 8:
commit 6cad4b84f42481ab1513cfa49721857c9cc9e304 (HEAD -> master)
Author: Cameron Adler <ca748420@ohio.edu>
Date:   Sat May 14 23:40:23 2022 -0400

    Initial commit

Answer 9:
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 1.02 KiB | 524.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/ca748420/git-lab.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

Answer 10: No

Answer 11: The command is rejected since the online repository doesn't match the local repository

Answer 12: Yes

Answer 13:
Mode                LastWriteTime     Length Name
----                -------------     ------ ----
-a---         5/15/2022  12:08 AM        302 .gitignore
-a---         5/15/2022  12:08 AM         11 README.md
