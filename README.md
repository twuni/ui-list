# 🥪 Virtualized List | Twuni UI

![Code Coverage by Test Suite][coverage]
![License][license]
[![Bundle Size][footprint]][bundlephobia]
[![Current Release Version][version]][npm]
![Weekly Downloads][downloads]
[![Sponsors][sponsors]][become-a-sponsor]
[![Known Vulnerabilities][vulnerabilities-badge]][vulnerabilities]

A tiny virtualized list implementation for Preact apps.

## Features

 * Tiny footprint (~2KB gzipped!)
 * No dependencies (BYO Preact/HTM)
 * MIT license
 * Browser-native ESM friendly (designed specifically to require zero build tools to run)

## Installing

```bash
npm install --save @twuni/ui-list
```

Yarn users, you know what to do instead.

## Usage

The following examples are written in JSX format, for brevity.

### Example: Basic Usage

```jsx
import List from '@twuni/ui-list';

<List
  count={1000000}
  renderItem={(index) => <p>Item {index}</p>}
/>
```

There are only two props:

 * `count` (number) - How many items are in the list, total.
 * `renderItem` (function(number)) - A function that, given the index of the item to render, returns the rendered list item.

[coverage]: https://img.shields.io/badge/coverage-0%25-critical
[license]: https://img.shields.io/npm/l/@twuni/ui-list
[footprint]: https://img.shields.io/bundlephobia/minzip/@twuni/ui-list
[version]: https://img.shields.io/npm/v/@twuni/ui-list
[downloads]: https://img.shields.io/npm/dw/@twuni/ui-list
[sponsors]: https://img.shields.io/github/sponsors/canterberry
[become-a-sponsor]: https://github.com/sponsors/canterberry
[npm]: https://npmjs.com/package/@twuni/ui-list
[bundlephobia]: https://bundlephobia.com/package/@twuni/ui-list
[vulnerabilities-badge]: https://snyk.io/test/npm/@twuni/ui-list/badge.svg
[vulnerabilities]: https://snyk.io/test/npm/@twuni/ui-list
