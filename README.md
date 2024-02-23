
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   
</head>
<body>
    <h1>Git Steps for Angular Project</h1>
    <ol>
        <li>Initialize a new git repository in your project directory:</li>
        <pre><code>git init</code></pre>
        <li>Stage all the changes in your project directory for the first commit:</li>
        <pre><code>git add .</code></pre>
        <li>Commit the staged changes with a message describing the changes:</li>
        <pre><code>git commit -m "first commit"</code></pre>
        <li>Check the status of your repository to see the changes that have been staged:</li>
        <pre><code>git status</code></pre>
        <li>Rename the current branch to "main":</li>
        <pre><code>git branch -M master</code></pre>
        <li>Add a remote repository where your local repository will be pushed:</li>
        <pre><code>git remote add origin https://github.com/shubhampatil101220/ChatApp.git</code></pre>
        <li>Push the changes from your local repository to the remote repository:</li>
        <pre><code>git push -u origin main</code></pre>
    </ol>
</body>
</html>
