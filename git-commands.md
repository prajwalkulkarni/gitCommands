<ul>
  <li>git init -> initialize git in local repository.</li>

  <li>git rebase <i>branch_name</i> -> Merge changes into a branch without adding an extra commit. As if, a current branch was cut from the latest state of the parent branch </i></li>

<li>git add "filename" -> Staging the files for tracking version control</li>

<li>git status(under sub-directory) -> Status(modified, untracked) of files on the current branch</li>

<li>git log -> log information</li>

<li>git commit -m <i>PATH_SPEC</i> 'message' "filename" -> commit file(save changes) with commit message. `PATH_SPEC` is optional, skipping it would commit only staged files</li>

<li>git remote add origin <i>git repo url</i> -> Set remote origin.</li>

<li>git remote set-url origin <i>git repo url</i> ->change remote url.</li>

<li>git push -u origin <b>branch-name</b> -> push files to repo. args -> -f merge pull request on selected branch</li>

<li>git checkout <i>commit-id</i> -> Revert to previous commit(previous refers to any of the past commits)</li>

<li>git checkout <i>branch-name</i> -> switch to existing branch</li>

<li>git checkout -b <i>new-branch</i> -> create a new branch</li>
  
  <li> git switch <i>branch-name</i> -> switch to existing branch</li>
  
  <li>git remote -v -> remote url</li>

<li>git -a branch -> List all working branches</li>

<li>git branch --delete <i>branch-name</i> -> Delete a branch.</li>
  
  <li>git branch -D <i>branch-name</i> -> Force delete a branch.</li>

<li><b>fork</b> -> create a copy of repository. </li>

<li><b>star</b> -> bookmark project.</li>

<li><b>pull request</b> -> request to review changes.</li>

<li>git pull <b>repo-name</b> <b>branch</b> -> pull from the specified branch. get pull = git fetch + git merge</li>
  
  <li> git log --branches --oneline --graph -> get hash of all commits</li>
<li>git cherry-pick <COMMIT_HASH> -> Extract changes done in a commit on another branch</li>
<li>git branch -m <i>old_name</i> <i>new_name</i> -> Rename branch</li>
<li>git stash -> save working changes without commiting</li>
<li>git stash pop -> Pop stashed changes</li>

<li>git merge --abort -> Abort a merge commit, typically done when a pull results in a merge conflict</li>
<li>git reset --merge -> Revert conflicts arising due to diff in stashed changes and the current head</li>
<li>git reset --soft HEAD~n -> n is the number of commits to revert</li>
<li>git reset 'HEAD@{n}' -> Move tip forward n times/undo git reset</li>
</ul>
<hr>

