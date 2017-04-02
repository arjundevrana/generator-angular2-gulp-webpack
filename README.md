# generator-angular2-gulp-webpack

NOTE: This project is deprecated and is not longer maintained. Following the release of Angular2 it is largely unnecessary and probably no longer works with later releases.

This is a simple Yeoman generator to create Angular2 projects using Gulp. This generator uses webpack to bundle up all the files resulting in a faster website with fewer HTTP requests. However this makes development tedious since builds are not that fast, so by default development is done using System.js and compiling Typescript in the browser. This lets you rapidly prototype and iterate while still minimizing the number of files and making it efficient to serve the completed app in production.

Run `npm install -g generator-angular2-gulp-webpack` to install. You might need to use sudo on Linux. Once the generator is installed create a directory where you want your project to live and change to it. Then just run `yo angular2-gulp-webpack` to generate the project.

To serve the app in development run `npm start` and go to http://localhost:3000 to view your app. To compile the app for production run `npm run build` or `gulp build` and the production ready app is in the dist folder.

Inspired by [ng2-webpack-play](https://github.com/pkozlowski-opensource/ng2-webpack-play).
## License

MIT
