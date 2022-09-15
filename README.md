# README

Generate static build:

`npm run build`

Publish to GitHub Pages with:

`git subtree push --prefix dist origin gh-pages`

Available at:

`https://opengeospatial.github.io/dev-ogc-org-sprint-landing-18/`


Add git submodule:

`git submodule add -b gh-pages https://github.com/opengeospatial/dev-ogc-org-sprint-landing-18.git sprints/18`

Update git submodule:

`git submodule foreach git pull origin gh-pages`
