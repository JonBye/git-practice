# git-practice
<h2>Get Source, make changes and push to main</h2>

<h4>1st you need to install git</h4>
<a href="https://git-scm.com/download/win">Install Git</a>
<br/>

<h4>2nd Clone or Create an existing Repository. Check your GitHub account for list of Repos</h4>
<p>git clone www.github.com/JonBye/git-practice</p>
<br/>

<h4>3rd Make a change using VS Code. Once done, add the change to git. You can specify single file, multiple files or all files</h4>
<ul>
  <li>Single : git add .\README.md</li>
  <li>Multiple :  git add .\README.md, .\LICENSE.md</li>
  <li>All : git add .</li>
</ul>
<br/>

<h4>4th Once changes added to git change tracker you can commit the change(s) locally</h4>
<p>git commit</p>

<h4>5th When ready to commit to master use Push</h4>
<p>git push</p>

<h4>6th To get Latest</h4>
<p>git pull<p>

<h4>How Git Works (excerpt from : https://www.atlassian.com/git)</h4> 
<p>Here is a basic overview of how Git works:</p>

<h2>Branching and Merging</h2>

<h4>Create a branch</h4>
<p>git branch BranchName</p>

<h4>Switch to work in new branch</h4>
<p>git switch BranchName</p>

<h4>When ready to merge to Main branch, Open a pull request</h4>
<p>git pull-request</p>

<h4>Merge branche into main</h4>
<p>git merge BranchName Main</p>
