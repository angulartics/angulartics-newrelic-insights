# angulartics-newrelic-insights

[![NPM version][npm-image]][npm-url] [![NPM downloads][npm-downloads-image]][npm-downloads-url] [![Bower version][bower-image]][bower-url] [![Dependencies status][dep-status-image]][dep-status-url] [![MIT license][license-image]][license-url] [![Build Status](https://travis-ci.org/prestonvanloon/angulartics-newrelic-insights.svg?branch=master)](https://travis-ci.org/prestonvanloon/angulartics-newrelic-insights)

New Relic Insights plugin for Angulartics

## Install

First, make sure you've read installation and setup instructions for [Angulartics](https://github.com/prestonvanloon/angulartics#install).

Second, make sure you've read setup instructions for [New Relic Browser Insights](https://docs.newrelic.com/docs/browser/new-relic-browser/installation-configuration/adding-apps-new-relic-browser).

Then you can install this package either with `npm` or with `bower`.

### npm

```shell
npm install angulartics-newrelic-insights
```

Then add `angulartrics.newrelic.insights` as a dependency for your app:

```javascript
require('angulartics')

angular.module('myApp', [
  'angulartics',
  require('angulartics-newrelic-insights')
]);
```

> Please note that core Angulartics doesn't export the name yet, but it will once we move it into [the new organization](http://github.com/angulartics).

### bower

```shell
bower install angulartics-newrelic-insights
```

Add the `<script>` to your `index.html`:

```html
<script src="/bower_components/angulartics-newrelic-insights/dist/angulartics-newrelic-insights.min.js"></script>
```

Then add `angulartrics.newrelic.insights` as a dependency for your app:

```javascript
angular.module('myApp', [
  'angulartics',
  'angulartrics.newrelic.insights'
]);
```

## Documentation

Documentation is available on the [Angulartics site](http://angulartics.github.io/).

## Development

```shell
npm run build
```

## Maintainers

- @gampleman

## License

[MIT](LICENSE)

[npm-image]: https://img.shields.io/npm/v/angulartics-newrelic-insights.svg
[npm-url]: https://npmjs.org/package/angulartics-newrelic-insights
[npm-downloads-image]: https://img.shields.io/npm/dm/angulartics-newrelic-insights.svg
[npm-downloads-url]: https://npmjs.org/package/angulartics-newrelic-insights
[bower-image]: https://img.shields.io/bower/v/angulartics-newrelic-insights.svg
[bower-url]: http://bower.io/search/?q=angulartics-newrelic-insights
[dep-status-image]: https://img.shields.io/david/prestonvanloon/angulartics-newrelic-insights.svg
[dep-status-url]: https://david-dm.org/prestonvanloon/angulartics-newrelic-insights
[license-image]: http://img.shields.io/badge/license-MIT-blue.svg
[license-url]: LICENSE
