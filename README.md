## Build to Git

into angular.js
`"outputPath": "docs",`

Run:

`$ ng build --prod --base-href "https://GithubUserName.github.io/GithubRepoName/"`

**Note:** Make sure you put in your Github username in “GithubUserName” and the repository name you created in “GithubRepoName” sections of the URL.

`$ ng build --prod`

When everithing is commited in `Main` or `Master`

Go to Repo Settings in Github
Scroll down to pages
In `Source`
Select Branch `Main` and `Docs`

**Wait a few minutes** until your site is built and published.

Go to the link provided by Github and hard refresh if it is necessary.

**NOTE** it seems that some times you should create into `Docs` a `404.html` file and copy in there everithing from `index.html`.