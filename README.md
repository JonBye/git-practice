# git-practice
<h2>Get Source, make changes and push to main</h2>

<h4>1st you need to install git</h4>
<a href="https://git-scm.com/download/win">Install Git</a>
<br/>

<h4>Once Git is installed, Clone or Create an existing Repository. Check your GitHub account for list of Repos</h4>
<p>git clone www.github.com/JonBye/git-practice</p>
<br/>

<h4>Make a change using VS Code. Once done, add the change to git. You can specify single file, multiple files or all files</h4>
<ul>
  <li>Single : git add .\README.md</li>
  <li>Multiple :  git add .\README.md, .\LICENSE.md</li>
  <li>All : git add .</li>
</ul>
<br/>

<h4>Once changes added to git change tracker you can commit the change(s) locally</h4>
<p>git commit</p>

<h4>When ready to commit to master use Push</h4>
<p>git push</p>

<h4>To get Latest</h4>
<p>git pull<p>

<h2>Branching and Merging</h2>

<h4>Create a branch, setup remote branch and change tracking</h4>
<p>git branch BranchName </p>

<h4>Switch to work in new branch</h4>
<p>git switch BranchName --set-upstream origin BranchName</p>

<h4>When ready to merge to Main branch, switch to master branch and merge BranchName</h4>
<p>git switch master</p>
<p>git pull</p>
<p>git merge BranchName</p>