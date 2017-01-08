# use git -rebase to set up a less messy git repo

### Example for a Node project
* add a new repo on github website 
* add gitginore and LICENSE in the setup page
* copy the git URL on your repo page
* `mkdir` and `cd` to you project
* `npm init` and input your project name and git link and stuff
* `git remote add {local name} {URL}`
* `git pull --rebase {local name} {branch name || master}`
* `git add .` `git commit -m ''` `git push {local name} {branch name}`

### benefits
* no need to write `.gitignore` 
* setup local name
* less confilcts


