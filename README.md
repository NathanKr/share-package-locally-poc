<h2>Motivation</h2>
share code between projects. in this poc the project are on the same repository but in general they are on different repositories and this should work any way


<h2>Setup</h2>
<h3>package (provider)</h3>
<ol>
<li>Create a package.json . specify 
<p>name - the name of the package</p>
<p>version - version of the package</p>
<p>main - what is the file entry point</p>
</li>
<li>Create the project</li>
<li>In the project root cmd : npm link</li>
<li>To remove the link to the local packages registry: 
<p>npm unlink</p>
</li>
</ol>

<h3>app (consumer)</h3>
<ul>
<li>In the project root cmd 
<p>npm link package_name </p>
</li>
<li>To remove the link to the local packages registry: 
<p>npm unlink</p>
</li>
</ul>