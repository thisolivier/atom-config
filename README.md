## Atom-Config
Configuration for your Atom IDE ccentred on the Fictus Syntax and Seti UI themes.

# What is this?
- Includes list of packages for front end development
- Customised stylesheet for clearer work with the Seti UI theme
- Font for Syntax editing included

# How do I do this?
Navigate to ~/.atom (the hidden atom folder in your user directory on macOS). Initialise a new repo in there, and add this repo, or your fork of it (recommended) as the remote, set your local branch to track it, and pull the files:

$ git remote add origin https://github.com/user/repo.git 
$ git branch --set-upstream-to=origin/master master  
$ git pull --allow-unrelated-histories

What you do next depends on if you want to merge your existing config with this repo, or replace it. I recommend replacing, because conflict resolution is boring (that's a life lesson).

$ git reset --hard

If you want to merge, then get filtering those conflicts, add everything, and push. I found I had to pull, merge and push again;

git pull --allow-unrelated-histories
git git commit -m "Merging things"
git push


