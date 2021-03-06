# React On a Roll

A Cordova template using React On(senUI) a(nd) Roll(up).

[![npm version](https://badge.fury.io/js/react-on-a-roll.svg)](https://badge.fury.io/js/react-on-a-roll)

# Getting Started

## What is included?

- [React & React DOM](https://facebook.github.io/react/)
- [OnsenUI & React OnsenUI](https://onsen.io/)
- [Babel](https://babeljs.io/)
- [PostCSS](http://postcss.org/)
- [Rollup](https://rollupjs.org/)
- [Eslint](http://eslint.org/)
- [Prettier](https://github.com/prettier/prettier)
- [Livereload](http://livereload.com/)
- [Fetch](https://github.com/whatwg/fetch), [Promise and much more ES6 polyfills](https://babeljs.io/docs/usage/polyfill/).

## Installation

```
cordova create MyApp --template=react-on-a-roll
cd MyApp
yarn
```

This will install dependencies and add the browser platform.

# Work using the browser platform.

```
yarn start
```

This will compile the application source code and will start a development server. The app will be reloaded every time the source code changes. You can use Cordova plugins in the browser because it uses the browser platform under the hood.

# Run in a simulator or a device

```
yarn build && cordova run ios android
```

# Build for production

```
yarn run dist && cordova build ios android --release
```

# License

MIT
