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
