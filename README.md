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

**NOTE** it seems that some times you should create into `Docs` a `404.html` file and copy in there everithing from `index.htm

------------------------------

## Circle CI
To adapt CI to your project you need:

1. Create your `yaml` configuration. This can be just copy from this project, is very basic just run the unit tests and build the app.
2. Log in into Circle CI.
3. Go to your `Projects`.
4. Set Up Project button.
5. It will ask you for your yaml, just upload the example you have in this repo path: `.circleci/config.yml`.
6. Thats it.!!!!

------------------------------

## Cypress
How Install:
`npm install cypress --save-dev`

Into `cypress.json` copy:

```json
{
  "baseUrl": "http://localhost:4200"
}
```
Run: `npx cypress open`

------------------------------

## Storybook
How Install:

`npx sb init`

`npm run storybook`

Use:
In the module we will use the componentes (shared.modiled recommended). Import the story component `../stories/xxx.component`and copy it into `declarations`, now we can use the Story HTML tag.

------------------------------

## Bootstrap
How Install:

`ng add ngx-bootstrap` in CMD recomended.

Then copy the js from ng bootstrap webpage into `index.html`.

------------------------------
