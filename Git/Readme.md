GIT 


1.Git e-Book(for free) - https://git-scm.com/book/en/v2

2.Atlassian GIT Tutorials: https://www.atlassian.com/git/tutorials

3.Git trial : https://try.github.io

4.Git Branching - https://learngitbranching.js.org/

# Some Git CODES :<br>
## Create a new repository :<br>
> git init<br>
## Checkout a repository :<br>
### create a working copy of a local repository by running the command :<br>
> git clone /path/to/repository<br>
### when using a remote server, your command will be :<br>
> git clone username@host:/path/to/repository <br>
## Workflow :<br>
Your local repository consists of three "trees" maintained by git.<br> The first one is your Working Directory which holds the actual files.<br> The second one is the Index which acts as a staging area and finally the HEAD which points to the last commit you've made.<br><br>
![Workflow](http://rogerdudler.github.io/git-guide/img/trees.png)<br>
## Add and Commit :<br>
You can propose changes (add it to the Index) using<br>
> git add <filename><br>
> git add *<br>
### To actually commit these changes use <br>
> git commit -m "Commit message"<br>
### Now the file is committed to the HEAD, but not in your remote repository yet.<br>
## Pushing the changes made :<br>
To send those changes to your remote repository, execute <br>
> git push origin master<br>
### If you haven't cloned an existing repository and want to connect your repository to a remote server,add it with :<br>
> git remote add origin <server>



