   "Answer 1" 
git --version 2.17.1


      "Answer 2"
user.name=Brody Reynolds
user.email=br750418@ohio.edu


	"Answer 3"
usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

These are common Git commands used in various situations:

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
   checkout   Switch branches or restore working tree files
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


	"Answer 4"
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	DEADJOE

nothing added to commit but untracked files present (use "git add" to track)



	"Answer 5"
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md


	"Answer 6"
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md
	new file:   answers.md


	"Answer 7"
On branch master
nothing to commit, working tree clean


	"Answer 8"
commit 338d23e0da9414bd5d8ef17be5a455275da2e884 (HEAD -> master)
Author: Brody Reynolds <br750418@ohio.edu>
Date:   Tue Aug 31 16:24:41 2021 -0400

    Initial commit


	"Answer 9"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean


	"Answer 10"
No


	"Answer 11"

To https://github.com/br750418/git-lab.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/br750418/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.


	"Answer 12"
The changes did go through so yes

remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From https://github.com/br750418/git-lab
   e493d9f..f61e2ed  main       -> origin/main
Updating e493d9f..f61e2ed
Fast-forward
 README.md | 1 +
 1 file changed, 1 insertion(+)

	"Answer 13"
.  ..  .git  .gitignore  README.md





