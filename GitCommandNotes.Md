## Git Commands

**`git --version`** : Git current version.

`U - untracked`

`A - added or staged`

`C - Commited`

**`cd <file name>`** : To change the current working directory to the specified file name.

**`cd ..`** : Go back to the previous working directory.

#### Global Setups :
1. `git config --global user.name "name"`
2. `git config --global user.email "email@female.com"`

<hr>

#### commands need to know :

- **`git init`** : Initialize a new git repository.

- **`git status`** : Check the state of the working directory and the staging area.

- **`git clone <repository-url>`** : Clone a repository.

- **`git add <file>`** : Add a file to the staging area.

- **`git add .`** : Add all files changes to the staging area.

- **`git rm <file>`** : Remove a file from the index and working directory.

- **`git  commit -m "Message"`** : Commit the staged changes.

- **`git log`** : List the commit history.

- **`git log --oneline`** : list the commit history in one line.

- **`git branch`** : List of all local branches.

- **`git branch -M <branch-name>`** : Rename the current branch.

- **`git branch <branch-name>`** : Create a new branch.

- **`git branch -d <branch-name>`** : Delete a branch.

- **`git branch -c <branch-name>`** : Create a branch and switch it.

- **`git Checkout <branch-name>`** : Switch to another branch.

- **`git marge <branch-name>`** : Merge specified branch into the current branch.

- **`git diff`** : Check the unstaged changes.

<hr>

#### Clone :
git clone link (from github code) =>go to folder(cd) => create branch and switch => after edit code => git add =>git commit -m "first commit" => git push -u origin footer => (main coder) git fetch => git merge footer => git push origin main => (second coder)git fetch => git pull .

<hr>

#### Add collaborator :
github => settings => collaborators => add people => username => add


