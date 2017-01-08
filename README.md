# use git -rebase to set up a less messy git repo

### Example for a Node project
1. add a new repo on github website 
2. add gitginore and LICENSE in the setup page
3. copy the git URL on your repo page
4. `mkdir` and `cd` to you project
5. `npm init` and input your project name and git link and stuff
6. `git remote add {remote name} {URL}`
7. `git pull --rebase {remote name} {branch name || master}`
8. `git add .` `git commit -m ''` `git push {remote name} {branch name}`

### benefits
* no need to write `.gitignore` 
* setup remote name
* less confilcts


