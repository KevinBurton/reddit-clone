# RedditClone

This project was generated with [angular-cli](https://github.com/angular/angular-cli) version 1.0.0-beta.15.

## Development server
Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive/pipe/service/class`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.
`ng build --env prod` or `ng build --prod`

`ng build --prod --base-href /` now you can go into the dist folder and test with another browser like

`(cd dist && python -m SimpleHTTPServer 8080)`

or

`(cd dist && python -m http.server 8080)`

If all looks good in the pre-deployment (above) then you can push it to github pages

`git subtree push --prefix dist/ origin gh-pages`

Go to the repository and got to the branch. Click on the settings button and go down to GitHub Pages.

As an example, the current `ng github-pages:deploy` does the following:

* creates GitHub repo for the current project if one doesn't exist
* rebuilds the app at the current HEAD
* creates a local gh-pages branch if one doesn't exist
* moves your app to the gh-pages branch and creates a commit
* edit the base tag in index.html to support github pages
* pushes the gh-pages branch to github
* returns back to the original HEAD

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/). 
Before running the tests make sure you are serving the app via `ng serve`.

## Deploying to Github Pages

Run `ng github-pages:deploy` to deploy to Github Pages.

## Further help

To get more help on the `angular-cli` use `ng --help` or go check out the [Angular-CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
