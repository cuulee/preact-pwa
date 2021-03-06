# [preact-pwa](https://preact-pwa.appspot.com/)

A `Super fast progressive web app` with a small footprint & minimal dependancies.  

Features universal rendering, redux, state-driven routing, preact, & service workers.  Crunched & optimized with rollup, buble, optimize-js, & purify-css.

Live version: [https://preact-pwa.appspot.com/](https://preact-pwa.appspot.com/)

## bundle sizes & perf
```
Bundle Size:            27.55 KB, Gzipped size: 9.79 KB
Webpage test:           A, A, A
pagespeed:              100
lighthouse:             100
```
we can shave off ~10 KB, ~3kb Gzipped by pruning `preact-redux` & manually connecting

## Features

- Progressive Web App enabled with [service workers](https://developers.google.com/web/fundamentals/getting-started/primers/service-workers)
- Offline capable with [service workers](https://developers.google.com/web/fundamentals/getting-started/primers/service-workers)
- Universal JavaScript (isomorphic rendering)
- Asset Versioning, long term caching, & cache busting for browser that do not support service workers via [node-rev](https://www.npmjs.com/package/node-rev)
- Modern JavaScript syntax with [ES6](https://github.com/lukehoban/es6features) via [buble](https://buble.surge.sh/guide/).
- Performant bundles via [rollup](http://rollupjs.org/).
- Component-based UI architecture via [Preact](https://preactjs.com/).
- Application state management w/time-travel debugging via [Redux](https://github.com/gaearon/redux).
- CSS built with [Sass](http://sass-lang.com/) and optimized with [purify-css](https://github.com/purifycss/purifycss).
- Async actions handled with [redux-thunk](https://github.com/gaearon/redux-thunk), [isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch), and [promises](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise).
- Node server is built with [express](http://expressjs.com/).
- Linting is handled with [Standard](http://standardjs.com/).

## Getting Started

### Prerequisites

Make sure that [Node v7](https://nodejs.org/en/download/releases/) is installed.

Make sure that [yarn](https://github.com/yarnpkg/yarn) is installed.

### Instructions

First, clone the repo

```bash
$ git clone https://github.com/ezekielchentnik/preact-pwa
```

Then, install all dependencies:

```bash
$ yarn
```

Finally, to run the project for development:

```bash
$ yarn dev
```

Or, to run the project for production:

```bash
$ yarn start
```

License

MIT
