Assignment 1.4 — Git Essentials I
Terminal Commands (VS Code):


git --version
mkdir git-project
cd git-project
git init
git config user.name "Your Name"
git config user.email "you@example.com"

echo "<h1>Hello World</h1>" > index.html
git status
git add .
git commit -m "Initial HTML page"

echo "<p>My first project</p>" >> index.html
git add .
git commit -m "Added paragraph"

echo "<h2>Learning Git</h2>" >> index.html
git add .
git commit -m "Added heading"

git log --oneline
code .

Note: Replace the username and email with your own. Install Git from git-scm.com if git is not recognized.

Submission: Take 2 screenshots:

Project folder showing index.html in VS Code.

Terminal showing 3 commits using git log --oneline.

