# Create a table
| Command			| Description				|
|-------------------------------/---------------------------------------/
| git init			| Initialize a new Git repository	|
| git clone <url>		| Clone a repository			|
| git status			| Clone a repository			|
| git add <file>      		| Stage (add) a file			|
| git commit -m "message"       | Commit staged changes with a message  |
| git push origin main      	| Push commits to the remote main branch|
| git pull origin main      	| Pull updates from remote main branch  |
| git remote -v             	| Show remote connections               |
| git branch                	| List local branches                   |
| git checkout <branch>     	| Switch to a branch                    |
| git merge <branch>        	| Merge a branch into current branch    |
| ssh-keygen                	| Generate a new SSH key                |
| cat ~/.ssh/id_rsa.pub     	| View your SSH public key              |

# Step 1: Check if 'Cheatsheet' is a file or a directory
ls -l

# (After checking, follow one of the two paths below)

# If 'Cheatsheet' is a FILE, open it directly to edit
nano Cheatsheet

# If 'Cheatsheet' is a FOLDER, first move into it
cd Cheatsheet

# Then create a new file inside called 'git_cheatsheet.txt'
nano git_cheatsheet.txt

# (Inside nano, paste your Git cheatsheet content, save with Ctrl+O, Enter, then exit with Ctrl+X)

# Now, go back to your project root folder (if you entered the Cheatsheet folder)
cd ..

# Step 2: Add all changes (your new or edited cheatsheet) to Git staging
git add .

# Step 3: Commit the changes with a nice message
git commit -m "Added Git and SSH setup commands to Cheatsheet"

# Step 4: Push the changes to GitHub
git push origin main
