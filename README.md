# Mostly followed this tutorial for setting up dotbot https://jsonmart.in/how-to-easily-back-up-and-restore-your-linux-configuration-software--using-git-and-dotbot
#This was my firt time trying this, so no real config changes in my dotfiles. Now I know this works I will start to customize my dotfiles.

#Good notes that helped me.
# Create a new repository on the command line(Repo must be created on github first)
 
touch README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/c0ldlimit/vimcolors.git
git push -u origin master
 
# Push an existing repository from the command line
 
git remote add origin https://github.com/c0ldlimit/vimcolors.git
git push -u origin master
