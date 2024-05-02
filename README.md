# React Bootstrap Typeahead

A [React](https://reactjs.org/)-based typeahead that relies on [Bootstrap](https://getbootstrap.com/) for styling and was originally inspired by Twitter's [typeahead.js](https://github.com/twitter/typeahead.js). It supports both single- and multi-selection and is compliant with [WAI-ARIA authoring practices](https://www.w3.org/TR/wai-aria-practices-1.1/#combobox). Try the [live examples](http://ericgio.github.io/@swenkerorg/doloribus-facilis-quidem/).

[![npm version](https://img.shields.io/npm/v/@swenkerorg/doloribus-facilis-quidem.svg?style=flat-square)](https://www.npmjs.com/package/@swenkerorg/doloribus-facilis-quidem)
[![npm downloads](https://img.shields.io/npm/dm/@swenkerorg/doloribus-facilis-quidem.svg?style=flat-square)](https://www.npmjs.com/package/@swenkerorg/doloribus-facilis-quidem)
[![CI](https://github.com/swenkerorg/doloribus-facilis-quidem/actions/workflows/ci.yml/badge.svg)](https://github.com/swenkerorg/doloribus-facilis-quidem/actions/workflows/ci.yml)
[![Codecov](https://img.shields.io/codecov/c/github/ericgio/@swenkerorg/doloribus-facilis-quidem?label=Codecov&logo=codecov&style=flat-square)](https://app.codecov.io/gh/ericgio/@swenkerorg/doloribus-facilis-quidem/)
[![MIT License](https://flat.badgen.net/github/license/ericgio/@swenkerorg/doloribus-facilis-quidem)](LICENSE.md)

Please note that documentation and examples apply to the most recent release and may no longer be applicable if you're using an outdated version.

## Installation

```
npm install --save @swenkerorg/doloribus-facilis-quidem
```

or

```
yarn add @swenkerorg/doloribus-facilis-quidem
```

Include the module in your project:

```jsx
import { Typeahead } from '@swenkerorg/doloribus-facilis-quidem'; // ES2015
var Typeahead = require('@swenkerorg/doloribus-facilis-quidem').Typeahead; // CommonJS
```

#### UMD Build

Development and production builds are included in the NPM package. Alternatively, you can get them from [CDNJS](https://cdnjs.com/libraries/@swenkerorg/doloribus-facilis-quidem) or [unpkg](https://unpkg.com/@swenkerorg/doloribus-facilis-quidem/).

## Documentation

- [Basic Usage](docs/Usage.md)
- [Data](docs/Data.md)
- [Filtering](docs/Filtering.md)
- [Rendering](docs/Rendering.md)
- [Public Methods](docs/Methods.md)
- [API & Props](docs/API.md)
- [Upgrade Guide](docs/Upgrading.md)

## CSS

While the component relies primarily on Bootstrap, some additional styling is needed. You should include the provided CSS file in your project:

```js
// Import as a module in your JS
import '@swenkerorg/doloribus-facilis-quidem/css/Typeahead.css';
```

or

```html
<!-- Link as a stylesheet in your HTML -->
<link
  rel="stylesheet"
  href="https://unpkg.com/@swenkerorg/doloribus-facilis-quidem/css/Typeahead.css"
/>
```

### Bootstrap 5
In an effort to support Bootstrap 5, this package also contains a CSS file named `Typeahead.bs5.css` that should be included alongside the base CSS file above.

## Examples

Try the [live examples](http://ericgio.github.io/@swenkerorg/doloribus-facilis-quidem/), which also include code samples. If you'd like to modify the examples, clone the repository and run `npm install` and `npm start` to build the example file. You can then open the HTML file locally in your browser.

You can also try out the following sandbox examples:

- [Windowing with large data sets](https://codesandbox.io/p/sandbox/stoic-river-4q1yjrzrn0)
- [Asynchronous pagination](https://codesandbox.io/p/sandbox/heuristic-pateu-zfjwjq)
- [Combobox](https://codesandbox.io/p/sandbox/friendly-bose-kkmyd)
- [Validation and feedback](https://codesandbox.io/p/sandbox/amazing-mendeleev-4w01px4z6x)
- [Custom loader & clear button](https://codesandbox.io/p/sandbox/practical-jang-gn3kn)
- [Multi-select with reorderable drag & drop tokens](https://codesandbox.io/p/sandbox/misty-water-u43sf)
- [Keep the menu open during multi-selection](https://codesandbox.io/p/sandbox/eloquent-germain-nr2y4)
- [Single-select with floating label (BS5)](https://codesandbox.io/p/sandbox/upbeat-paper-8c2j6b)

If you have an example use case that would be useful to others, please create a sandbox and submit a pull request to add it to the list!

## Browser Support

Recent versions of the following browsers are supported:

- Chrome
- Firefox
- Edge
- Safari

Special thanks to [BrowserStack](https://www.browserstack.com) for providing cross-browser testing support.

[![http://i.imgur.com/9aLP6Fx.png?1](http://i.imgur.com/9aLP6Fx.png?1)](https://www.browserstack.com)

## License

[MIT](https://github.com/swenkerorg/doloribus-facilis-quidem/blob/master/LICENSE.md)
