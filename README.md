# UBDC Snowpack GH Pages Demo

This application contains a simple configuration to run and deploy HTML, CSS and JS websites on Github pages.

Configuration is managed with `snowpack` and deployment is run through GH Actions. Packages are managed with `npm`.

## How it works
---
The action contained in the actions workflow __Build Into -b `gh-pages`__ will create a build configuration inside the `gh-pages` branch.

Subsequently, the __pages build and deployment__ workflow will publish a version of the `gh_pages` branch at the root to Github Pages.

🚀 Voila ...

## What you can do?
---
1. Clone this repository - git clone https://github.com/urbanbigdatacentre/snowpack-ghpages.git
2. For starters ... edit `index.js` and `index.html`
3. Run `npm run build`
4. Run `npm start`
5. Create your own Github Repository to work with - https://docs.github.com/en/get-started/quickstart/create-a-repo
6. Under the pages tab of your repository settings - set up Github pages to track the `root` folder within the `gh-pages` branch
7. Add this 👆 repository as a remote - `git remote add origin <your repo>`
8. Add your files - `git add .`
9. Commit your files - `git commit -m "Initial Commit with My Changes`
10. Push your changes - `git push -u origin main`
11. The actions to deploy your site are setup to run automatically on a new push to the `main` branch.
12. Wait a few minutes - or follow the progress in the repositories __Actions__ tab. That's it!

## Running Locally
---
### npm start

Runs the app in the development mode.
Open http://localhost:8080 to view it in the browser.

The page will reload if you make edits.
You will also see any lint errors in the console.

### npm run build

Builds a static copy of your site to the `docs` folder.
Your app is ready to be deployed!

---


