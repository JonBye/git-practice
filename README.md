# git-practice
<h2>Practicing git commands and flow</h2>

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

<h4>4th Once changes added to git change tracker you can commit the change(s) locally<h4>
<p>git commit</p>

<h4>5th When ready to commit to master use Push<h4>
<p>git push</p>

<h4>6th To get Latest<h4>
<p>git pull<p>

<h4>How Git Works (excerpt from : https://www.atlassian.com/git)</h4> 
<p>Here is a basic overview of how Git works:</p>
<ul>  
  <li>Create a "repository" (project) with a git hosting tool (like Bitbucket)</li>
  <li>Copy (or clone) the repository to your local machine</li>
  <li>Add a file to your local repo and "commit" (save) the changes</li>
  <li>"Push" your changes to your main branch</li>
  <li>Make a change to your file with a git hosting tool and commit</li>
  <li>"Pull" the changes to your local machine</li>
  <li>Create a "branch" (version), make a change, commit the change</li>
  <li>Open a "pull request" (propose changes to the main branch)</li>
  <li>"Merge" your branch to the main branch</li>
</ul>
