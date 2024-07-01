# react-static-pro-plugin-reach-router

A react static pro plugin that adds @reach/router

## Installation

- Install this plugin and peer dependencies:

```bash
$ yarn add react-static-pro-plugin-reach-router @reach/router
```

- Add the plugin to your `static.config.js`:

```javascript
export default {
  plugins: ['react-static-pro-plugin-reach-router'],
}
```

- (Optional) Configure the plugin:

```javascript
export default {
  plugins: [
    [
      'react-static-pro-plugin-reach-router',
      {
        RouterProps: {
          // These props will be passed to the underlying `Router` component
        },
      },
    ],
  ],
}
```
