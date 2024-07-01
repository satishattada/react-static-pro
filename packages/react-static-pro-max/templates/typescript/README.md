# react-static-pro-max - TypeScript Template

To use this template, run `react-static-pro-max create` and use the `typescript` template.

## Path Aliases for Absolute Imports

`react-static-typescript-plugin` supports path aliases. It has been set up in this template.

```js
// tsconfig.json
{
  // ...
    "paths": {
      "@components/*": ["src/components/*"]
    },
  // ...
}

// this works in your React app
import FancyDiv from '@components/FancyDiv'
```
