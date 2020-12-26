# Demo For beginning Git and GitHub
<ul>
<li><em>When we first save this file or "commit" this file we need to supply a placeholder text else the default would be chosen .</em></li>
<li><em>When we edit this file, we have certain options to "commit" or save these changes, we see that the placeholder text has been changed, we go ahead and commit these changes with the preselected option, i.e. commit to the main branch</em></li>
<li><em>For cloning/downloading the repository to work on your local system , we use the following steps : </em>
<ul>
<li>First setup git on your PC, <a href="https://www.youtube.com/embed/RGOj5yH7evk?start=660" >see this Tutorial to install Git</a></li>
<li>If you need to clone/download directly using HTTPS url the later steps are not necessary that deal with the SSH key,For this just type <div><strong >git clone <em>https-url-of-repository</em></strong></div></li>
<li>For using SSH keys, which are secure shell login without having to login eveytime, follow the steps  <a href ="https://docs.github.com/en/free-pro-team@latest/github/authenticating-to-github/connecting-to-github-with-ssh">here</a> </li>
<li>After setting up SSH key we use same syntax as for HTTPS url but paste the SSH url, and we are able to download it and edit it locally on our PC</li>
</ul> </li>
<li><em>To save the changes we use <strong>git commit</strong> command but before that we type <strong>git status</strong> to see which files where edited, deleted or modified. If we have added a new file in the repository we see it under Untracked heading therefore we need to tell to git that we have created this file and to track this particular file(s) using <strong>git add</strong> command and the name of the files to be tracked after that , for eg: <div><strong>git add index.html</strong></div> or if we want every change that we made to be tracked we just supply a period '.' <div><strong>git add .</strong></div></em></li>
<li><em>To save these changes we use the <strong>git commit</strong> command with a modification "-m" to notify the placeholder text in this commit followed by the placeholder text and (optional) second "-m" followed by description for this commit <div><strong>git commit -m "Added index.html and updated README.md" -m "some description"</strong></div></em></li>
<li><em>Now this only saves the changes on our local machine and not on GitHub where our project is hosted, to make these changes in the live project on GitHub we use the command <strong>git push origin master</strong></em></li>
</ul>

