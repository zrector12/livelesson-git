
- `git init` : initialize current folder as a git repository
- `git clone <URL> ` : brings the git repo from <URL> to current folder
- `git status` : tells us what we need to know about our repository

- `git add <FILE>` : adds <FILE> to the staging area
- `git commit` : open a text editor to write commit message
   - `git commit -m "Message"` wrties message as a commit without a text editor.

`git log`:shows the log history of our commits
- `git log --oneline` uses one line to show history

- `git diff`: compare current uncommited state with last known state
-`git diff --staged`: runs git diff between staging area and last knon state
-`git diff HEAD~<NUMBER>` : compares HEAD with commit <NUNBER?ago (relative)
-`git diff <HASH>` compares HEAD with the commit in <HASH>

-`git restore -- source <HASH OR HEAD~> <FILE>` : restore file to <HASH OR HEAD~>
-`git checkout <HASH OR HEAD~ <FILE>`: restores file to <HASH OR HEAD>
-`git checkout <HASH OR HEAD>`: if you forget the file, you end up in detach
-`git checkout main`: go back to main
-`git switch main`: go back to main

#remotes title
-`git remote add <NAME> <URL>`: adds the <URL> as a remote with the name <NAME>
  <NAME> is by convention called 'origin'
-`git remote rm <NAME>`: removes the remote called <NAME>
-``git remote -v`: look at all the remotes you have 
-`git push <WHERE> <WHAT>`: pushes the <WHAT> branhc to <WHERE>
          `git push origin main`

-`git pull <WHERE> <WHAT>`: pulls the <WHAT> branch in <WHERE> to local computer

