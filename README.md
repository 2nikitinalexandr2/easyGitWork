# easyGitWork
## easyGitWork manual steps:
* Install git/gitbash(Windows)
* go to your cmd/shell and input command:
  +  `git --version` check git version and git working
  +  `git config --list` to check config
* ### use ssh to clone or push:
  +  `git config -- global user.name "Your_First_Name Y_Second_Name"`
  +  `git config -- global user.email "email_from_your_git_remote_account"`
  +  `git config -l ` to check config
  +  `git clone URL_FROM_WEB_VERSION_GIT` (gihub.com/gitlab.com/etc./) like https://github.com/2nikitinalexandr2/easyGitWork.git (GREEN BUTTON "CODE")
  +  ` git clone https://github.com/2nikitinalexandr2/easyGitWork.git`
  +   change files or add file in directory easyGitWork( directory that you clone from remote)
      + `git status` 
      + `git add .` or `git add all` or `git add CERTAIN_FILE` (CERTAIN_FILE that was change and you want to track it and push to remote)
      + `git commit -m "a comment with meaning"`
      + `git push`
* ### use https to clone or push:
  +  `git config -- global user.name "Your_First_Name Y_Second_Name"`
  +  `git config -- global user.email "email_from_your_git_remote_account"`
  +  `git config -l ` to check config
  +  go to YOUR_USER_DIRECTORY to .ssh directory `cd /c/Users/user/.ssh`
  +  cat or less id_rsa.pub and copy it
  +  go to your remote account and paste it ( Settings/SSH_and_GPG_Keys/New_SSH_Key)
  +  `git clone URL_FROM_WEB_VERSION_GIT` (gihub.com/gitlab.com/etc./) like git@github.com:2nikitinalexandr2/easyGitWork.git (GREEN BUTTON "CODE")
  +  `git clone git@github.com:2nikitinalexandr2/easyGitWork.git`
  +   change files or add file in directory easyGitWork( directory that you clone from remote)
      + `git status` 
      + `git add .` or `git add all` or `git add CERTAIN_FILE` (CERTAIN_FILE that was change and you want to track it and push to remote)
      + `git commit -m "a comment with meaning"`
      + `git push`
