---


---

<ul>
<li>Make sure you have a Heroku account. Create one if not. <a href="https://signup.heroku.com" title="Click here to create">Click here to create</a></li>
<li>Make sure you have deploy rights for the project you’re trying to deploy - ask someone with admin rights to add you to the project.</li>
<li>Add heroku remotes using the command: <code>git remote add Remote-Name Remote-URL</code>. Check the remotes by running<code>git remote -v</code>. <code>fetch</code> and <code>push</code> link should exist for every remote, similar to image below for <code>treats-api-web</code> project with the addition of the origin remote.<br>
<img src="https://www.showdoc.cc/server/api/common/visitfile/sign/ea51b904e63e6c8a3e2b3edc401fd835?showdoc=.jpg" alt="For reference" title="For reference"></li>
<li>Install Heroku CLI. <a href="https://devcenter.heroku.com/articles/heroku-cli" title="Click here to install heroku">Click here to install heroku</a></li>
<li>Run <code>heroku login</code> to log in to heroku</li>
<li>Deploy using the command: <code>git push Remote-Name your-branch-name:master</code></li>
<li>Update the local branch by fetching from remote to make sure local has everything that is on remote.<br>
<strong>NOTE: local branch is being deployed by this process so be careful if there are any unpushed local commits.</strong></li>
</ul>
<hr>

<table>
<thead>
<tr>
<th>Project-Name</th>
<th>Environment(Remote-Name)</th>
<th>Remote-URL</th>
</tr>
</thead>
<tbody>
<tr>
<td>treats-api-web</td>
<td>trstage01</td>
<td><a href="https://git.heroku.com/trstage01.git">https://git.heroku.com/trstage01.git</a></td>
</tr>
<tr>
<td>treats-api-web</td>
<td>trstage02</td>
<td><a href="https://git.heroku.com/trstage02.git">https://git.heroku.com/trstage02.git</a></td>
</tr>
<tr>
<td>treats-api-web</td>
<td>trproduction</td>
<td><a href="https://git.heroku.com/serene-sierra-8540.git">https://git.heroku.com/serene-sierra-8540.git</a></td>
</tr>
<tr>
<td>surprisehr</td>
<td>staging</td>
<td><a href="https://git.heroku.com/shr-web-stage.git">https://git.heroku.com/shr-web-stage.git</a></td>
</tr>
<tr>
<td>surprisehr</td>
<td>production</td>
<td><a href="https://git.heroku.com/pure-springs-61728.git">https://git.heroku.com/pure-springs-61728.git</a></td>
</tr>
</tbody>
</table>
