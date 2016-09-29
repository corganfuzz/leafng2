Angular2-Leaflet-Starter
========================

A web mapping application starter based on Angular 2 and Leaflet. This project demo includes basic mapping features:

-	[x] Display base maps from different sources

-	[x] Integrate Font-Awesome

-	[x] Initialize map based on user's IP location

-	[x] Geocode address and zoom to result location

-	[x] Add/remove markers on the map

Support the [Angular 2 official release](https://github.com/angular/angular/blob/master/CHANGELOG.md#200-2016-09-14) now!

See how it looks at [demo page](http://haoliangyu.github.io/angular2-leaflet-starter/).

FAQ
--------------

### How about Leaflet 1.0?

Yeap! As soon as the [type definition](https://github.com/DefinitelyTyped/DefinitelyTyped/blob/master/leaflet/leaflet.d.ts) for 1.0 is done, I will update the leaflet version used in this project.

### How about new feature?

Since this project has been reached its initial goal to provide a small and clean code base for Angular 2 and Leaflet integration, currently there is no plan for new feature development. However, I am open to suggestions and PRs. If you think it's beneficial for **general developers** to add something new, please feel free to submit an issue for dicussion.

How to develop
--------------

This project requires [npm](https://www.npmjs.com/), [typings](https://www.npmjs.com/package/typings),  [webpack](http://webpack.github.io/docs/installation.html).

1.	Run `npm install` to install all dependencies.

2.	Run `typings install` to install type definition.

3.	Run `webpack` to build the project.

4.	As a more convinient way, run the [webpack-dev-server](http://webpack.github.io/docs/installation.html) to set up the app at `http://localhost:8080`

Thanks to these awesome people!
-------------------------------

-	[Rodolphe Eveilleau](https://github.com/rdphv)

- [Wolfgang Becker](https://github.com/vimwb)

Looking for another solution?
-------------------------------

[angular2-mapboxgl-starter](https://github.com/haoliangyu/angular2-mapboxgl-starter) is an Angular 2 project seed with [MapboxGL](https://www.mapbox.com/mapbox-gl-js/api/), a mapping library designed for [vector tile](https://www.mapbox.com/help/define-vector-tiles/).
