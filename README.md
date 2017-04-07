# api documentation for  [react-google-maps (v4.11.0)](https://tomchentw.github.io/react-google-maps/)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-google-maps.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-google-maps) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-google-maps.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-google-maps)
#### React.js Google Maps integration component

[![NPM](https://nodei.co/npm/react-google-maps.png?downloads=true)](https://www.npmjs.com/package/react-google-maps)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-google-maps/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-react-google-maps_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-google-maps/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-google-maps/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-google-maps/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "tomchentw",
        "email": "developer@tomchentw.com",
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
            "email": "developer@tomchentw.com",
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
            "name": "tomchentw",
            "email": "developer@tomchentw.com"
        }
    ],
    "name": "react-google-maps",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.0",
        "react-dom": "^0.14.0 || ^15.0.0"
    },
    "readme": "ERROR: No README data found!",
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



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module react-google-maps](#apidoc.module.react-google-maps)
1.  [function <span class="apidocSignatureSpan">react-google-maps.</span>Circle ()](#apidoc.element.react-google-maps.Circle)
1.  [function <span class="apidocSignatureSpan">react-google-maps.</span>DirectionsRenderer ()](#apidoc.element.react-google-maps.DirectionsRenderer)
1.  [function <span class="apidocSignatureSpan">react-google-maps.</span>DrawingManager ()](#apidoc.element.react-google-maps.DrawingManager)
1.  [function <span class="apidocSignatureSpan">react-google-maps.</span>GoogleMap ()](#apidoc.element.react-google-maps.GoogleMap)
1.  [function <span class="apidocSignatureSpan">react-google-maps.</span>GoogleMapLoader ()](#apidoc.element.react-google-maps.GoogleMapLoader)
1.  [function <span class="apidocSignatureSpan">react-google-maps.</span>InfoWindow ()](#apidoc.element.react-google-maps.InfoWindow)
1.  [function <span class="apidocSignatureSpan">react-google-maps.</span>KmlLayer ()](#apidoc.element.react-google-maps.KmlLayer)
1.  [function <span class="apidocSignatureSpan">react-google-maps.</span>Marker ()](#apidoc.element.react-google-maps.Marker)
1.  [function <span class="apidocSignatureSpan">react-google-maps.</span>OverlayView ()](#apidoc.element.react-google-maps.OverlayView)
1.  [function <span class="apidocSignatureSpan">react-google-maps.</span>Polygon ()](#apidoc.element.react-google-maps.Polygon)
1.  [function <span class="apidocSignatureSpan">react-google-maps.</span>Polyline ()](#apidoc.element.react-google-maps.Polyline)
1.  [function <span class="apidocSignatureSpan">react-google-maps.</span>Rectangle ()](#apidoc.element.react-google-maps.Rectangle)
1.  [function <span class="apidocSignatureSpan">react-google-maps.</span>SearchBox ()](#apidoc.element.react-google-maps.SearchBox)



# <a name="apidoc.module.react-google-maps"></a>[module react-google-maps](#apidoc.module.react-google-maps)

#### <a name="apidoc.element.react-google-maps.Circle"></a>[function <span class="apidocSignatureSpan">react-google-maps.</span>Circle ()](#apidoc.element.react-google-maps.Circle)
- description and source-code
```javascript
function Circle() {
  _classCallCheck(this, Circle);

  _get(Object.getPrototypeOf(Circle.prototype), "constructor", this).apply(this, arguments);

  this.state = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-google-maps.DirectionsRenderer"></a>[function <span class="apidocSignatureSpan">react-google-maps.</span>DirectionsRenderer ()](#apidoc.element.react-google-maps.DirectionsRenderer)
- description and source-code
```javascript
function DirectionsRenderer() {
  _classCallCheck(this, DirectionsRenderer);

  _get(Object.getPrototypeOf(DirectionsRenderer.prototype), "constructor", this).apply(this, arguments);

  this.state = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-google-maps.DrawingManager"></a>[function <span class="apidocSignatureSpan">react-google-maps.</span>DrawingManager ()](#apidoc.element.react-google-maps.DrawingManager)
- description and source-code
```javascript
function DrawingManager() {
  _classCallCheck(this, DrawingManager);

  _get(Object.getPrototypeOf(DrawingManager.prototype), "constructor", this).apply(this, arguments);

  this.state = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-google-maps.GoogleMap"></a>[function <span class="apidocSignatureSpan">react-google-maps.</span>GoogleMap ()](#apidoc.element.react-google-maps.GoogleMap)
- description and source-code
```javascript
function GoogleMap() {
  _classCallCheck(this, GoogleMap);

  _get(Object.getPrototypeOf(GoogleMap.prototype), "constructor", this).apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-google-maps.GoogleMapLoader"></a>[function <span class="apidocSignatureSpan">react-google-maps.</span>GoogleMapLoader ()](#apidoc.element.react-google-maps.GoogleMapLoader)
- description and source-code
```javascript
function GoogleMapLoader() {
  _classCallCheck(this, GoogleMapLoader);

  _get(Object.getPrototypeOf(GoogleMapLoader.prototype), "constructor", this).apply(this, arguments);

  this.state = {
    map: null
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-google-maps.InfoWindow"></a>[function <span class="apidocSignatureSpan">react-google-maps.</span>InfoWindow ()](#apidoc.element.react-google-maps.InfoWindow)
- description and source-code
```javascript
function InfoWindow() {
  _classCallCheck(this, InfoWindow);

  _get(Object.getPrototypeOf(InfoWindow.prototype), "constructor", this).apply(this, arguments);

  this.state = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-google-maps.KmlLayer"></a>[function <span class="apidocSignatureSpan">react-google-maps.</span>KmlLayer ()](#apidoc.element.react-google-maps.KmlLayer)
- description and source-code
```javascript
function KmlLayer() {
  _classCallCheck(this, KmlLayer);

  _get(Object.getPrototypeOf(KmlLayer.prototype), "constructor", this).apply(this, arguments);

  this.state = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-google-maps.Marker"></a>[function <span class="apidocSignatureSpan">react-google-maps.</span>Marker ()](#apidoc.element.react-google-maps.Marker)
- description and source-code
```javascript
function Marker() {
  _classCallCheck(this, Marker);

  _get(Object.getPrototypeOf(Marker.prototype), "constructor", this).apply(this, arguments);

  this.state = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-google-maps.OverlayView"></a>[function <span class="apidocSignatureSpan">react-google-maps.</span>OverlayView ()](#apidoc.element.react-google-maps.OverlayView)
- description and source-code
```javascript
function OverlayView() {
  _classCallCheck(this, OverlayView);

  _get(Object.getPrototypeOf(OverlayView.prototype), "constructor", this).apply(this, arguments);

  this.state = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-google-maps.Polygon"></a>[function <span class="apidocSignatureSpan">react-google-maps.</span>Polygon ()](#apidoc.element.react-google-maps.Polygon)
- description and source-code
```javascript
function Polygon() {
  _classCallCheck(this, Polygon);

  _get(Object.getPrototypeOf(Polygon.prototype), "constructor", this).apply(this, arguments);

  this.state = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-google-maps.Polyline"></a>[function <span class="apidocSignatureSpan">react-google-maps.</span>Polyline ()](#apidoc.element.react-google-maps.Polyline)
- description and source-code
```javascript
function Polyline() {
  _classCallCheck(this, Polyline);

  _get(Object.getPrototypeOf(Polyline.prototype), "constructor", this).apply(this, arguments);

  this.state = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-google-maps.Rectangle"></a>[function <span class="apidocSignatureSpan">react-google-maps.</span>Rectangle ()](#apidoc.element.react-google-maps.Rectangle)
- description and source-code
```javascript
function Rectangle() {
  _classCallCheck(this, Rectangle);

  _get(Object.getPrototypeOf(Rectangle.prototype), "constructor", this).apply(this, arguments);

  this.state = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-google-maps.SearchBox"></a>[function <span class="apidocSignatureSpan">react-google-maps.</span>SearchBox ()](#apidoc.element.react-google-maps.SearchBox)
- description and source-code
```javascript
function SearchBox() {
  _classCallCheck(this, SearchBox);

  _get(Object.getPrototypeOf(SearchBox.prototype), "constructor", this).apply(this, arguments);

  this.state = {};
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
