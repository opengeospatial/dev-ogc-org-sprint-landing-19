# README

Generate static build:

`npm run build`

Publish to GitHub Pages with:

`git subtree push --prefix dist origin gh-pages`

Available at:

`https://opengeospatial.github.io/dev-ogc-org-sprint-landing-19/`


Add git submodule:

`git submodule add -b gh-pages https://github.com/opengeospatial/dev-ogc-org-sprint-landing-19.git sprints/19`

Update git submodule:

`git submodule foreach git pull origin gh-pages`
