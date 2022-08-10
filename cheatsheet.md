# Terminal Commands

## Main Terminal Commands

- **Pwd**: tells the current directory
- **Ls**: lists the contents of the current directory
- **Cd**: moves back to the home (user) directory
- **Cd (directory name)**: changes to specified directory
- **Cd ..**: changes to parent directory (changes to grandparent if extra . is added, and so on)
- **Mkdir (directory name)**: creates a new directory
- **Touch (file name)**: either creates a new file or updates the last modified date of existing file
- **Rm (file name)**: permanently deletes file
- **Rmdir**: permanently deletes an empty directory
- **Rm -r**: permanently deletes a directory and its contents
- **Open (file name)**: opens a file or directory
- **Mv (file name) (directory name)**: moves specified file to specified directory
- **Mv (file name) (new file name)**: renames file
- **Cp (file name) (directory name)**: copies file to specified directory
- **Clear**: wipes clean the terminal window


## Useful extras

- **.**: specifies how far above the folders tree to navigate (1 - parent dir, 2 - grandparent, etc)
- **-**: indicates that the following character is a flag
- **--**: indicates that the following word is a flag
- **Man (command)**: shows a manual about specified command and its flags


## Git Terminal Commands

- **Git init**: initialises a git repository in current folder
- **Git status**: informs which files in the repository have been modified
- **Git add**: stages the changes made to the files in the repository
- **Git commit -m "(commit message)"**: creates a record of the changes made (the message describes these changes)
- **Git log**: shows information about what's been committed
- **Git revert (first 7 digits of commit number)**: reverts a commit
- **Git remote add origin (ssh repo link)**: links current folder to a GitHub repository
- **Git push origin main**: uploads the code to GitHub
- **Git pull origin main**: downloads the changes made to the local repository
