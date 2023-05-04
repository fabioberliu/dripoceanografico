# TEST
modifica
BERLIU@LAB4-16 MINGW64 ~/Desktop/git/dripoceanografico (main)
$ ls
README.md

BERLIU@LAB4-16 MINGW64 ~/Desktop/git/dripoceanografico (main)
$ pwd
/c/Users/berliu/Desktop/git/dripoceanografico

BERLIU@LAB4-16 MINGW64 ~/Desktop/git/dripoceanografico (main)
$ ls -al
total 5
drwxr-xr-x 1 BERLIU 1049089 0 May  4 12:32 ./
drwxr-xr-x 1 BERLIU 1049089 0 May  4 12:32 ../
drwxr-xr-x 1 BERLIU 1049089 0 May  4 12:38 .git/
-rw-r--r-- 1 BERLIU 1049089 8 May  4 12:32 README.md

BERLIU@LAB4-16 MINGW64 ~/Desktop/git/dripoceanografico (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

BERLIU@LAB4-16 MINGW64 ~/Desktop/git/dripoceanografico (main)
$ git log
commit 14e326273e1ed19227bd069971a71dac7f17b5ba (HEAD -> main, origin/main, origin/HEAD)
Author: fabioberliu <132049095+fabioberliu@users.noreply.github.com>
Date:   Thu May 4 12:17:41 2023 +0200

    Update README.md

commit d0a4069c7f5ded858b7f0f80e0170af4dd75b476
Author: fabioberliu <132049095+fabioberliu@users.noreply.github.com>
Date:   Fri Apr 28 09:47:49 2023 +0200

    Initial commit

BERLIU@LAB4-16 MINGW64 ~/Desktop/git/dripoceanografico (main)
$ nano README.md

BERLIU@LAB4-16 MINGW64 ~/Desktop/git/dripoceanografico (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

BERLIU@LAB4-16 MINGW64 ~/Desktop/git/dripoceanografico (main)
$ git log
commit 14e326273e1ed19227bd069971a71dac7f17b5ba (HEAD -> main, origin/main, origin/HEAD)
Author: fabioberliu <132049095+fabioberliu@users.noreply.github.com>
Date:   Thu May 4 12:17:41 2023 +0200

    Update README.md

commit d0a4069c7f5ded858b7f0f80e0170af4dd75b476
Author: fabioberliu <132049095+fabioberliu@users.noreply.github.com>
Date:   Fri Apr 28 09:47:49 2023 +0200

    Initial commit

BERLIU@LAB4-16 MINGW64 ~/Desktop/git/dripoceanografico (main)
$ git add README.md

BERLIU@LAB4-16 MINGW64 ~/Desktop/git/dripoceanografico (main)
$d qw1
bash: d: command not found

BERLIU@LAB4-16 MINGW64 ~/Desktop/git/dripoceanografico (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md


BERLIU@LAB4-16 MINGW64 ~/Desktop/git/dripoceanografico (main)
$ git co
git: 'co' is not a git command. See 'git --help'.

The most similar commands are
        commit
        clone
        log

BERLIU@LAB4-16 MINGW64 ~/Desktop/git/dripoceanografico (main)
$ git commit -m "MODIFICADRIPOCEANOGRAFICO"
[main e7301d5] MODIFICADRIPOCEANOGRAFICO
 Committer: FABIO BERLIU <BERLIU@iisspeano.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 2 insertions(+), 1 deletion(-)

BERLIU@LAB4-16 MINGW64 ~/Desktop/git/dripoceanografico (main)
$ git log
commit e7301d55cb11391d993464101c1f5aae9d93e6d4 (HEAD -> main)
Author: FABIO BERLIU <BERLIU@iisspeano.local>
Date:   Thu May 4 12:54:04 2023 +0200

    MODIFICADRIPOCEANOGRAFICO

commit 14e326273e1ed19227bd069971a71dac7f17b5ba (origin/main, origin/HEAD)
Author: fabioberliu <132049095+fabioberliu@users.noreply.github.com>
Date:   Thu May 4 12:17:41 2023 +0200

    Update README.md

commit d0a4069c7f5ded858b7f0f80e0170af4dd75b476
Author: fabioberliu <132049095+fabioberliu@users.noreply.github.com>
Date:   Fri Apr 28 09:47:49 2023 +0200

    Initial commit

BERLIU@LAB4-16 MINGW64 ~/Desktop/git/dripoceanografico (main)
$ git add --help

BERLIU@LAB4-16 MINGW64 ~/Desktop/git/dripoceanografico (main)
$ git co
commit   config

BERLIU@LAB4-16 MINGW64 ~/Desktop/git/dripoceanografico (main)
$ git config --global user.name "fabioberliu"

BERLIU@LAB4-16 MINGW64 ~/Desktop/git/dripoceanografico (main)
$ ^C

BERLIU@LAB4-16 MINGW64 ~/Desktop/git/dripoceanografico (main)
$ git config --global user.email "berliufabio@gmail.com"

BERLIU@LAB4-16 MINGW64 ~/Desktop/git/dripoceanografico (main)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 277 bytes | 277.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/fabioberliu/dripoceanografico.git
   14e3262..e7301d5  main -> main
