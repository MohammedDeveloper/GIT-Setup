# GIT-Setup
Install GIT for the OS(Windows/Mac/Linux) | https://git-scm.com/downloads

## For setting up the existing local repository with existing GIT repository
git init
git add .
git commit -m "<some message>"
git remote add origin <remote_git_repository_url>
git remote -v
git push origin master
- Error shall appear due to conflicts
git pull <remote_git_repository_url> (or) git pull <remote_git_repository_url> --allow-unrelated-histories
- Conflicts may appear as both repositories are individually developed
- Conflicts could be resolved by opening the file and merging changes using the IDE comparer tool
git add .
git commit -m "<some message>"
git push origin master

## For setting up the existing local repository with existing GIT repository
git clone <remote_git_repository_url>
- IDE shall provide all features

## References
https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet
https://www.siteground.com/tutorials/git/commands.htm
http://kbroman.org/github_tutorial/pages/init.html
https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/
