Git
📝 Git Commands
* git init
* git config --global user.name "User Name"
* git config --global user.email user.name@xyz.com
  The configuration is stored in your user profile (e.g., ~/.gitconfig on Linux/Mac or C:\Users\<username>\.gitconfig on Windows).
It applies to all repositories for the current user.
* git config --global user.email user.name@xyz.com
The configuration is specific to a single repository.
* git branch
* git add *
* git commit -m "msg"
* got commit -am "msg"

✅ Some important commands 

* git cherry-pick <commitId>
* git config --global core.autocrlf true
    For windows
* git config --global diff.tool vscode
* git config --global difftool.vscode.cmd "code --wait --diff $LOCAL $REMOTE"
* git config --global --unset diff.tool
* git config --global --unset difftool.vscode.cmd
* git config --global core.auto "code --wait"
* git cat-file -p HEAD
* git rm --cached command is used to remove files from the Git index (staging area) without deleting them from the working directory.
    git add *
    git rm --cached filename.txt
    to remove the unwanted file from staging area.
* git clean -n
    Flags Summary:

Flag
	Description

-n
	Dry run: Show what would be removed.

-f
	Force removal of untracked files.

-d
	Include untracked directories in the cleanup.

-x
	Remove ignored files as well as untracked files.

-i
	Interactive mode: Ask before removing each file.


* git branch -vv
* git checkout origin/dev -- webapp/build.yaml
    fetch the single file from remote repo
*  git restore --source=origin/dev webapp/built.yaml 

🔑 Key links

* https://git-scm.com/book/en/v2
* https://git-scm.com/docs

https://www.powershellgallery.com/packages/posh-git/1.1.0

Following are the guide and link of all the available commands -

Setup and Config

* git
* config
* help
* bugreport
* Credential helpers

Getting and Creating Projects

* init
* clone

Basic Snapshotting

* add
* status
* diff
* commit
* notes
* restore
* reset
* rm
* mv

Branching and Merging

* branch
* checkout
* switch
* merge
* mergetool
* log
* stash
* tag
* worktree

Sharing and Updating Projects

* fetch
* pull
* push
* remote
* submodule

Inspection and Comparison

* show
* log
* diff
* difftool
* range-diff
* shortlog
* describe

Patching

* apply
* cherry-pick
* diff
* rebase
* revert

Debugging

* bisect
* blame
* grep



Guides

* gitattributes
* Command-line interface conventions
* Everyday Git
* Frequently Asked Questions (FAQ)
* Glossary
* Hooks
* gitignore
* gitmodules
* Revisions
* Submodules
* Tutorial
* Workflows
* All guides...

Email

* am
* apply
* format-patch
* send-email
* request-pull

External Systems

* svn
* fast-import

Administration

* clean
* gc
* fsck
* reflog
* filter-branch
* instaweb
* archive
* bundle

Server Admin

* daemon
* update-server-info

Plumbing Commands

* cat-file
* check-ignore
* checkout-index
* commit-tree
* count-objects
* diff-index
* for-each-ref
* hash-object
* ls-files
* ls-tree
* merge-base
* read-tree
* rev-list
* rev-parse
* show-ref
* symbolic-ref
* update-index
* update-ref
* verify-pack
* write-tree


