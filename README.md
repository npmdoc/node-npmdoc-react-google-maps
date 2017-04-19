# npmdoc-react-google-maps

#### api documentation for  [react-google-maps (v4.11.0)](https://tomchentw.github.io/react-google-maps/)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-google-maps.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-google-maps) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-google-maps.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-google-maps)

#### React.js Google Maps integration component

[![NPM](https://nodei.co/npm/react-google-maps.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-google-maps)

- [https://npmdoc.github.io/node-npmdoc-react-google-maps/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-google-maps/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-google-maps/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-google-maps/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-google-maps/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-google-maps/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "tomchentw",
        "url": "https://github.com/tomchentw"
    },
    "bugs": {
        "url": "https://github.com/tomchentw/react-google-maps/issues"
    },
    "config": {
        "mocha": "--compilers js:babel/register ./src/__tests__/*.spec.js ./src/**/__tests__/*.spec.js --require ./src/__tests__/__setup__.js"
    },
    "contributors": [
        {
            "name": "tomchentw",
            "url": "https://github.com/tomchentw"
        }
    ],
    "dependencies": {
        "can-use-dom": "^0.1.0",
        "google-maps-infobox": "^1.1.13",
        "invariant": "^2.1.1",
        "lodash.isequal": "^3.0.4",
        "marker-clusterer-plus": "^2.1.4",
        "react-prop-types-element-of-type": "^2.1.0",
        "scriptjs": "^2.5.8",
        "warning": "^2.1.0"
    },
    "description": "React.js Google Maps integration component",
    "devDependencies": {
        "babel": "^5.8.23",
        "babel-core": "^5.8.25",
        "babel-eslint": "^4.1.3",
        "codeclimate-test-reporter": "^0.1.1",
        "eslint": "^1.10.3",
        "eslint-config-airbnb": "^2.1.1",
        "eslint-plugin-react": "^3.12.0",
        "expect": "^1.12.1",
        "isparta": "^3.1.0",
        "istanbul": "^0.3.22",
        "jsdom": "^7.0.2",
        "mocha": "^2.3.3",
        "react": "^0.14.0",
        "react-dom": "^0.14.0",
        "rimraf": "^2.4.3",
        "tomchentw-npm-dev": "^3.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "077a7d937685b5ff359d0b6ebb54505adec68712",
        "tarball": "https://registry.npmjs.org/react-google-maps/-/react-google-maps-4.11.0.tgz"
    },
    "files": [
        "lib/",
        "src/",
        "CHANGELOG.md"
    ],
    "gitHead": "472e29ca95d97672b72f34dc2074adc70461d4f0",
    "homepage": "https://tomchentw.github.io/react-google-maps/",
    "keywords": [
        "React.js",
        "React",
        "react-component",
        "google",
        "map",
        "maps",
        "place",
        "places",
        "googlemap",
        "googlemaps",
        "google-map",
        "google-maps",
        "google map",
        "google maps",
        "GoogleMapsMixin",
        "Map",
        "Marker",
        "Polyline",
        "Polygon",
        "Circle",
        "Directions",
        "InfoWindow",
        "SearchBox"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "tomchentw"
        }
    ],
    "name": "react-google-maps",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.0",
        "react-dom": "^0.14.0 || ^15.0.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/tomchentw/react-google-maps.git"
    },
    "scripts": {
        "build": "babel src --out-dir lib",
        "build:watch": "npm run build -- --watch",
        "clean": "rimraf lib",
        "lint": "eslint .",
        "prebuild": "npm run lint && npm run clean",
        "pretest": "npm run lint",
        "pretest:cov": "npm run lint",
        "test": "mocha $npm_package_config_mocha",
        "test:cov": "babel-node ./node_modules/.bin/isparta cover --report lcov _mocha -- $npm_package_config_mocha",
        "test:watch": "npm test -- --watch"
    },
    "version": "4.11.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
