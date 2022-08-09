<h1>Terminal Commands</h1>

<h2> Main Terminal Commands</h2>
<ul>
<li>Pwd: tells the current directory</li>
<li>Ls: lists the contents of the current directory</li>
<li>Cd: moves back to the home (user) directory</li>
<li>Cd (directory name): changes to specified directory</li>
<li>Cd ..: changes to parent directory (changes to grandparent if extra . is added, and so on)</li>
<li>Mkdir (directory name): creates a new directory</li>
<li>Touch (file name): either creates a new file or updates the last modified date of existing file</li>
<li>Rm (file name): permanently deletes file</li>
<li>Rmdir: permanently deletes an empty directory</li>
<li>Rm -r: permanently deletes a directory and its contents</li>
<li>Open (file name): opens a file or directory</li>
<li>Mv (file name) (directory name): moves specified file to specified directory</li>
<li>Mv (file name) (new file name): renames file</li>
<li>Cp (file name) (directory name): copies file to specified directory</li>
<li>Clear: wipes clean the terminal window</li>
</ul>

<h2>Useful extras</h2>
<ul>
<li>.: specifies how far above the folders tree to navigate (1 - parent dir, 2 - grandparent, etc)</li>
<li>-: indicates that the following character is a flag</li>
<li>--: indicates that the following word is a flag</li>
<li>Man (command): shows a manual about specified command and its flags</li>
</ul>

<h2>Git Terminal Commands</h2>
<ul>
<li>Git init: initialises a git repository in current folder</li>
<li>Git status: informs which files in the repository have been modified</li>
<li>Git add: stages the changes made to the files in the repository</li>
<li>Git commit -m "(commit message)": creates a record of the changes made (the message describes these changes)</li>
<li>Git log: shows information about what's been committed</li>
<li>Git revert (first 7 digits of commit number): reverts a commit</li>
<li>Git remote add origin (ssh repo link): links current folder to a GitHub repository</li>
<li>Git push origin main: uploads the code to GitHub</li>
<li>Git pull origin main: downloads the changes made to the local repository</li>
</ul>