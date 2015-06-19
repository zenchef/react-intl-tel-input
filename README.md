# React-Intl-Tel-Input

Rewrite [International Telephone Input](https://github.com/Bluefieldscom/intl-tel-input) in React.js.


## Demo & Examples

Live demo: [patw0929.github.io/react-intl-tel-input](http://patw0929.github.io/react-intl-tel-input/)

To build the examples locally, run:

```
npm install
npm start
```

Then open [`localhost:8000`](http://localhost:8000) in a browser.


## Installation

The easiest way to use react-intl-tel-input is to install it from NPM and include it in your own React build process (using [Browserify](http://browserify.org), [Webpack](http://webpack.github.io/), etc).

You can also use the standalone build by including `dist/main.js` in your page. If you use this, make sure you have already included React, and it is available as a global variable.

```
npm install react-intl-tel-input --save
```


## Usage

```
var IntlTelInput = require('react-intl-tel-input');

<IntlTelInput css={['county-sel', 'district-sel', 'zipcode']}>Example</IntlTelInput>
```

### Properties

Please see the [Demo Page](http://patw0929.github.io/react-intl-tel-input/)


## Development (`src` and the build process)

**NOTE:** The source code for the component is in `src`. A UMD bundle is also built to `dist`, which can be included without the need for any build system.

To build, watch and serve the examples (which will also watch the component source), run `npm start`.

## Inspired by

[International Telephone Input](https://github.com/Bluefieldscom/intl-tel-input) - [@jackocnr](https://github.com/jackocnr)

## License

MIT

Copyright (c) 2015 patw.
