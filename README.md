# react-admonitions

> An admonitions React component, ported from remarkable-admonitions. Perfect for Docusaurus v2 and other React-based doc generators.

## [Demo]()

[![NPM](https://img.shields.io/npm/v/react-admonitions.svg)](https://www.npmjs.com/package/react-admonitions) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install --save react-admonitions
```

## Screenshots

![Example Pictures](assets/preview.png)

## Usage

```jsx
import React, { Component } from 'react'

import Admonition from 'react-admonitions'

class Example extends Component {
  render() {
    return (
      <Admonition type="warning" title="Do not do this">
        Admonition Content
      </Admonition>
    )
  }
}
```

## Props

| Name           | Default | Description                                                                                                            |
| -------------- | ------- | ---------------------------------------------------------------------------------------------------------------------- |
| **`type`**     | none    | What type of admonition you want to display. Valid options: `"warning"`, `"tip"`, `"caution"`, `"note"`, `"important"` |
| **`iconType`** | `"svg"` | The type of admonition icon. Valid options: `"svg"`, `"emoji"` |
| **`title`** | none | The, well, title of the admonition |

## License

MIT © [nebrelbug](https://github.com/nebrelbug)
