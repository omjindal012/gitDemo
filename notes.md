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









U -> Untracked
A -> Added
M -> Modified

red area -> deletion
yellow/green area -> addition