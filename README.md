# AMuench's ESLint Plugin

A collection of ESLint settings for Amuench's projects


## Installation

To install the plugin, install the plugin package with peer dependencies

```bash
npm install --save-dev eslint-config-amuench

or 

yarn add -D eslint-config-amuench
```

After that, just add the package to your `eslint` config file under the extends property:

```json

...

"extends": [
    "eslint-config-amuench",
]
...