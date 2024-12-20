<!-- GIT -->

U -> Untracked
A -> Added
M -> Modified

red area -> deletion
yellow/green area -> addition

1. git init -> to enable git tracking

2. (command + shift + .) -> to reveal hidden git folder in finder which is created when we executed the previous command

3. (git --version) -> check whether git is installed or not

4. (git config --list) -> to get list of config (helps to track changes in case of multiple users)
    -> add your username :- (git config --global user.name "Your Name")
    -> add your email :- (git config --global user.email "youremail@example.com")

5. (git add "file-name") -> it moves the file from working directory(changes section) to the staging area(staged changes section)
    -> Now if I make change in the above file added in staging area then those changes will be reflected in changes section
    -> (git add .) :- To add all the files in staging area

6. (git status) -> to check the status of changes in the file and we can revert that changes using back option in changes section

7. (git commit -m "message") -> to commit the changes

8. (git log) -> to see the list of commits

9. (git checkout (commit-hash)) -> moves to that point of code

10. (git branch) -> to check your branch name

11. (git checkout (branch)) -> to comeback to the latest code 

<!-- GITHUB -->

1. Create a repository in your github account where you want to save the changes
2. Copy the code from (Push an existing repository from the command line)
    <!-- git remote add origin https://github.com/omjindal012/gitDemo.git
    git branch -M main
    git push -u origin main -->
3. 
