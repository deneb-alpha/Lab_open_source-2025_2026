# Clone the new repo just created

`git clone git@github.com:deneb-alpha/Lab_open_source-2025_2026.git`

# Define the user and email to use for the commits in the repository

You can check your Git settings with: 

`git config user.name && git config user.email`

## set the user and email for the local repository

- `git config user.name "Your Name Here"`
- `git config user.email your@email.example`

For (global) default email (which is configured in your ~/.gitconfig):

- `git config --global user.name "Your Name Here"`
- `git config --global user.email your@email.example`

# Check the remotes of your local checkout

`git remote -vv`

~~~
origin  git@github.com:deneb-alpha/Lab_open_source-2025_2026.git (fetch)
origin  git@github.com:deneb-alpha/Lab_open_source-2025_2026.git (push)
~~~

# Quick setup of a git repo

## Create a new repository on the command line
~~~
echo "# Lab_open_source-2025_2026" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:deneb-alpha/Lab_open_source-2025_2026.git
git push -u origin main
~~~

## Push an existing repository from the command line

~~~
git remote add origin git@github.com:deneb-alpha/Lab_open_source-2025_2026.git
git branch -M main
git push -u origin main
~~~
