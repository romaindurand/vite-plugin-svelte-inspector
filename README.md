> If you are using `vite-plugin-svelte`, use the `inspector` options instead:
> https://github.com/sveltejs/vite-plugin-svelte/blob/main/docs/config.md#inspector

![logo](./src/logo.png)

# vite-plugin-svelte-inspector

Play with the [LIVE DEMO](https://stackblitz.com/edit/sveltejs-kit-template-default-gnpnjl).

## Installation

```sh
# pnpm
pnpm install vite-plugin-svelte-inspector -D

# yarn
yarn add vite-plugin-svelte-inspector -D

# npm
npm install vite-plugin-svelte-inspector -D
```

## Usage

### Add it to your SvelteKit project

```js
// filename: svelte.config.js

// for vue2
import Inspector from 'vite-plugin-svelte-inspector';

/** @type {import('@sveltejs/kit').Config} */
const config = {
  kit: {
    // ...
    vite: {
      plugins: [Inspector({})],
    },
  },
};

export default config;
```

### Configuration

__toggleComboKey__

_default: 'control+shift'_
      
e.g. : `Inspector({toggleComboKey: 'control+i'})`


### License

[MIT](/LICENSE)
