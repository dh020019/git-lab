answer 1:   git version 2.20.1 (Apple Git-117)

answer 2:   Daniels-MBP-2:git-lab DantheMan$ git config --list
            credential.helper=osxkeychain
            user.name=Daniel Horn
            user.email=dh020019@ohio.edu

answer 3:   These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone      Clone a repository into a new directory
   init       Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   reset      Reset current HEAD to the specified state
   rm         Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   branch     List, create, or delete branches
   checkout    Switch branches or restore working tree files
   commit     Record changes to the repository
   diff       Show changes between commits, commit and working tree, etc
   merge      Join two or more development histories together
   rebase     Reapply commits on top of another base tip
   tag        Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.

answer 4: 

On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	.DS_Store
	README.md
	answers.md

nothing added to commit but untracked files present (use "git add" to track)

answer 5:

On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	.DS_Store
	answers.md

answer 6: 

On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md
	new file:   answers.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	.DS_Store

answer 7:

On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)

	.DS_Store

nothing added to commit but untracked files present (use "git add" to track)

answer 8:

commit 5a7cf63d9c6202d3d90142d3c9c663ac52ef04f8 (HEAD -> master)
Author: Daniel Horn <dh020019@ohio.edu>
Date:   Tue Sep 1 16:59:18 2020 -0400

    Initial commit

answer 9:

On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   answers.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	.DS_Store

no changes added to commit (use "git add" and/or "git commit -a")

answer 10:

name: Daniel Horn
git ID: dh020019


answer 11:


answer 12:

<<<<<<< HEAD
name: Daniel Horn
git ID: dh020019
=======
CS 2400 section 109
>>>>>>> 5afe1a5e247676284d9a40d55e57955dc0e73a19

answer 13:

remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (4/4), done.
Daniels-MBP-2:cs2400 DantheMan$ ls -a
.		.DS_Store	git-lab		hw		summer-labs
..		git-lab-2	summer-hw
