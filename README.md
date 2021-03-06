# Readme

---
## Description

This repository contains source codes for buidling a web based demo from Radiant.Earth's platform similar to our demos website (https://demos.radiant.earth/). The demo in this repository uses the NDVI change tool to detect changes in vegetation cover after Hurricane Maria. 

## Getting Started

You need Python 2.x to build and run this demo. 

To get up and running, run `npm install` in your CLI in the project directory.

Then run `yarn` and `yarn build`.

Then run `grunt`. Your browser should automatically open `localhost:3000`.

That's it. You are good to go.

---

## Grunt
### Grunt Plugins
* [Grunt Browser Sync](https://www.npmjs.com/package/grunt-browser-sync)
* [Grunt Contrib Watch](https://www.npmjs.com/package/grunt-contrib-watch)
* [Grunt Postcss](https://www.npmjs.com/package/grunt-postcss)
	* Autoprefixer
	* cssnano
* [Grunt Sass](https://www.npmjs.com/package/grunt-sass)
* [Load Grunt Config](https://www.npmjs.com/package/load-grunt-config)
* [Load Grunt Tasks](https://www.npmjs.com/package/load-grunt-tasks)
* [Time Grunt](https://www.npmjs.com/package/time-grunt)
* [Grunt Newer](https://www.npmjs.com/package/grunt-newer)
	* Not currently in use
* Grunt Concurrent
	* Under consideration

---

#### Grunt Browser Sync
Live reload and browser syncing. This will automatically open `localhost:3001` and you can access broswesync settings at `localhost:3002`

#### Grunt Contrib Watch
Run predefined tasks whenever watched file patterns are added, changed or deleted. Currently this will compile sass and run postcss tasks

#### Grunt Postcss
Applies several post-processors to your CSS using PostCSS. Currently will run Autoprfixer and cssnano immediately after sass compiling

#### Grunt Sass
Compile Sass to CSS using node-sass/libsass

#### Load Grunt Config
Allows us to break up the Gruntfile config by task. Makes for a cleaner Gruntfile

#### Load Grunt Tasks
Load multiple grunt tasks using globbing patterns.

#### Time Grunt
Display the elapsed execution time of grunt tasks

#### Grunt Newer
*Not Currently In Use* Run Grunt tasks with only those source files modified since the last successful run.

#### Grunt Concurrent
*Under Consideration* Run grunt tasks concurrently

#### grunt-html-build
*Consider*


## Credits

This demo is built using on an initial mini-app development from Raster Foundry team (https://github.com/raster-foundry).

Imagery used in the examples are provided by Planet (https://www.planet.com/).
