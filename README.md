# npmdoc-react-google-maps

#### basic api documentation for  [react-google-maps (v6.3.0)](https://tomchentw.github.io/react-google-maps/)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-google-maps.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-google-maps) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-google-maps.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-google-maps)

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
    "dependencies": {
        "babel-runtime": "^6.11.6",
        "can-use-dom": "^0.1.0",
        "google-maps-infobox": "^1.1.13",
        "invariant": "^2.2.1",
        "lodash": "^4.16.2",
        "marker-clusterer-plus": "^2.1.4",
        "react-display-name": "^0.2.0",
        "react-prop-types-element-of-type": "^2.2.0",
        "scriptjs": "^2.5.8",
        "warning": "^3.0.0"
    },
    "description": "React.js Google Maps integration component",
    "devDependencies": {
        "babel-cli": "^6.16.0",
        "babel-core": "^6.16.0",
        "babel-eslint": "^7.2.2",
        "babel-plugin-lodash": "^3.2.9",
        "babel-plugin-transform-flow-comments": "^6.8.0",
        "babel-plugin-transform-runtime": "^6.15.0",
        "babel-plugin-typecheck": "^3.9.0",
        "babel-preset-es2015": "^6.16.0",
        "babel-preset-react": "^6.16.0",
        "babel-preset-stage-0": "^6.16.0",
        "codeclimate-test-reporter": "^0.4.1",
        "cross-env": "^4.0.0",
        "eslint": "^3.19.0",
        "eslint-config-react-app": "^0.6.2",
        "eslint-plugin-flowtype": "^2.32.1",
        "eslint-plugin-import": "^2.2.0",
        "eslint-plugin-jsx-a11y": "^4.0.0",
        "eslint-plugin-react": "^6.10.3",
        "history": "^2.1.2",
        "isomorphic-fetch": "^2.2.1",
        "prismjs": "^1.5.1",
        "raf": "^3.3.0",
        "raw-loader": "^0.5.1",
        "react": "^15.0.0",
        "react-bootstrap": "^0.30.3",
        "react-dom": "^15.0.0",
        "react-github-fork-ribbon": "^0.4.4",
        "react-helmet": "^3.1.0",
        "react-icons": "^2.2.1",
        "react-prism": "^4.0.0",
        "react-router": "^2.8.1",
        "react-router-bootstrap": "^0.23.1",
        "react-scripts": "^0.9.5",
        "react-toastr": "^2.8.1",
        "rimraf": "^2.5.4",
        "standard-version": "^4.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "ba7e0b3c2a3ad15ebdff55ecfe8c17a1c9cd8a6b",
        "tarball": "https://registry.npmjs.org/react-google-maps/-/react-google-maps-6.3.0.tgz"
    },
    "files": [
        "lib/",
        "src/lib",
        "CHANGELOG.md"
    ],
    "gitHead": "79b3f470bf0e8fd5aa79ca24680e24384d97b66d",
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
        "HeatmapLayer",
        "Map",
        "Marker",
        "Polyline",
        "Polygon",
        "Circle",
        "Directions",
        "InfoWindow",
        "SearchBox",
        "TrafficLayer"
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
        "react": "^15.0.0",
        "react-dom": "^15.0.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/tomchentw/react-google-maps.git"
    },
    "scripts": {
        "build:app": "react-scripts build",
        "build:lib": "cross-env NODE_ENV=production babel src/lib --out-dir lib",
        "clean": "rimraf lib",
        "commit:app": "git add -A && git commit -m 'docs: compile from src/app with react-scripts'",
        "commit:lib": "git add -A && git commit -m 'chore(lib): compile from src/lib using babel'",
        "eject": "react-scripts eject",
        "lint": "cross-env NODE_ENV=test eslint .",
        "prebuild:lib": "npm run lint && npm run clean",
        "precommit:app": "npm run build:app",
        "precommit:lib": "npm run build:lib",
        "prerelease": "npm run commit:lib && npm run commit:app",
        "pretest": "npm run lint",
        "release": "standard-version",
        "start": "react-scripts start",
        "test": "react-scripts test --env=jsdom",
        "test:once": "cross-env CI=true npm test"
    },
    "version": "6.3.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
