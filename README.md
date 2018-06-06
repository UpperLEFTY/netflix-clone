# netflix-clone
Netflix Clone,  search and recommend movies similar to Netflix.  I used React, Redux and React Router to create view layer for single page app. Configured Webpack 4 and Express to provide tools for both dev and prod env, such as Hot-reload, PostCSS, and Autoprefixer to ensure styles are supported across modern browsers.








User Story
user can see recommended movies on homepage.

user can see description of a movie when mouse is hovering on movie's thumbnail.

user can search for movies by titles.

user can see detail description when I click on a movie's thumbnail.

cast list is included in the description.

responsive to different screen size.

Usage
1. First install package cross-env globally
npm i -g cross-env

Ensure npm scripts work properly across Linux, Windows, and all environments.

2. install everything else
npm install

3a. run on localhost
develop environment, run webpack dev server

npm start

This will get the files running on http://localhost:8080 Webpack will watch for changes and update the browser when file changes.

3b. build dist directory
production environment, run webpack

npm run build

The minified JS bundle files including the output html file will be store in dist directory.

Appreciation for all the great online Learning Resources that are provided for free.
Great Community:
inspired by kuanhsuh, his post
Guide Line for Learning, FreeCodeCamp, link
Webpack:
Webpack Config Basics, by Matthew Hsiung, link
Webpack & CSS, by Matthew Hsiung, link
Webpack Config Advanced, by Matthew Hsiung, link
CSS:
Performant CSS Animations: Netflix Case Study, by Eli White's, link
CSS Animations Neflix carousel, by Matthew James Taylor, link
Netflix Style Carousel, by Jonathan Carroll, link
redux:
React+Redux+Webpack, by Kurt Weiberth, link
API:
themoviedb, link
