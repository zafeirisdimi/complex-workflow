# How to make a complex workflow in Github Actions #

## Challenge ##


<ul><h3>Develop a Complex Workflow:</h3>
<li><h4>Push trigger</h4></li>
<li><h4>Multiple runners with different operating systems</h4></li>
<li><h4>Job dependencies</h4></li>
</ul>


## Solution ##

<ol>
  <h3>Instruction to solve the challenge:</h3>
  <li>Starting your workflow file with a new repository.</li>
  <li>Use a push trigger to start it. </li>
  <li>The workflow should contain four jobs</li>
  <ul>
    <li>Job 1: ubuntu-latest</li>
    <li>Job 2: windows-latest</li>
    <li>Job 3: macos-latest</li>
    <li>Job 4: depens on job 1,2 and 3</li>
  </ul>
  <li>Print the date</li>
</ol>



