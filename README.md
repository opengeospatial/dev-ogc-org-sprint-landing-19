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

## Development server

Run `npm start` to start the development server. The site will be available at:

`http://localhost:3000`

The development server is based on [livereload](https://www.npmjs.com/package/livereload):

* The site is built to the `dist/` folder and served from there on `http://localhost:3000`. A file watcher rebuilds the pages, styles, scripts, and assets in `dist/` on the fly whenever you edit files in `src/`.
* The LiveReload client script is injected into every rendered page, and connects back to the LiveReload server (running on `http://localhost:35729/livereload.js` by default) through a websocket.
* Whenever a generated file in `dist/` changes, the LiveReload server notifies the connected browser and the page is automatically refreshed, so the changes you make to the code are reflected in the browser.

You can change the ports with the `PORT` (website, default `3000`) and `LIVERELOAD_PORT` (LiveReload server, default `35729`) environment variables.

> [!TIP]
> You can also run `npm run start:debug` to start the development server with a debugger attached to the build scripts.
