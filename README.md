# frontend-project-template

This is boilerplate code for simple front end projects, utilizing a task runner, gulp, which makes learning and development much easier.

## Basics
The default task, `gulp`, will spin up a webserver on a local port that compiles scss to CSS and also autoprefixes the CSS. BrowserSync will watch for any changes to a file ending in .html, .scss and .js  in the `src/` directory and will reload the page to reflect any changes. There will also be a link in dev tools to a sourcemap (this shows what scss file and what line of that file is responsible for the css rule in devtools for easy debugging).

The only task that needs to be manually called is `gulp` -- simply type `gulp` on the command line while in the root of the repo.

## How to use this repo
1. If you want to modify this repo for your own personal use, fork it then follow the instructions. Otherwise skip the optional step.
* Clone this repository
* Navigate to the the root of the cloned repo
* (OPTIONAL STEP) Reference the original boilerplate using `git remote add upstream URL`. This allows you to pull changes made to the boilerplate code in the future using `git pull upstream master`
* Initialize an empty repo on Github and change the remote's URL `git remote set-url origin git@github.com:USERNAME/REPOSITORY.git`
* Use`npm install` to get all required node modules
* Type `gulp` in the command line while in the directory to run default task
* Start coding
