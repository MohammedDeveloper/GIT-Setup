# GIT-Setup
Install GIT for the OS(Windows/Mac/Linux) | https://git-scm.com/downloads

## For setting up the existing local repository with existing GIT repository
1. git init
2. git add .
3. git commit -m "<some message>"
4. git remote add origin <remote_git_repository_url>
5. git remote -v
6. git push origin master
- Error shall appear due to conflicts
7. git pull <remote_git_repository_url> (or) git pull <remote_git_repository_url> --allow-unrelated-histories
- Conflicts may appear as both repositories are individually developed
- Conflicts could be resolved by opening the file and merging changes using the IDE comparer tool
8. git add .
9. git commit -m "<some message>"
10. git push origin master

## For setting up the existing local repository with existing GIT repository
git clone <remote_git_repository_url>
- IDE shall provide all features

## References
https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet
https://www.siteground.com/tutorials/git/commands.htm
http://kbroman.org/github_tutorial/pages/init.html
https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/
