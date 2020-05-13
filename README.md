# roweb2020

A Hugo playground for developing the rOpenSci 2020 redesign. 

**Requirements:**
Hugo, Node

## Build
- Navigate to `themes/2020/`
- Run `npm install` to install dependancies (bootstrap + node-sass)
- Run `npm build` to compile SASS

## Serve
- Run `hugo server --watch --verbose --buildDrafts --cleanDestinationDir --disableFastRender` from main directory to build and serve locally
- Run `npm run watch` from theme folder to watch for style changes, compile and trigger hot reload



