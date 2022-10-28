# @antv/dumi-theme-antv

[![NPM version](https://img.shields.io/npm/v/@antv/dumi-theme-antv.svg?style=flat)](https://npmjs.org/package/@antv/dumi-theme-antv)
[![NPM downloads](http://img.shields.io/npm/dm/@antv/dumi-theme-antv.svg?style=flat)](https://npmjs.org/package/@antv/dumi-theme-antv)

A theme package for the [dumi](https://next.d.umijs.org) framework.

## Usage

Install this theme into `devDependencies`:

```bash
$ npm i @antv/dumi-theme-antv -D
```

Configure it in dumi config file `.dumirc.ts`:

```ts
import { defineConfig } from 'dumi';

export defineConfig({
  themeConfig: {
    ...
  },
});
```

That's all, now you can execute `dumi dev` and enjoy this theme.

## Options

TODO

## Development

```bash
$ npm install
```

```bash
# build theme in dev
$ npm run dev

# link local deps
$ cd example && npm i

# start dev server to preview
npm run dev
```

dumi theme development documentation: https://next.d.umijs.org/theme

## LICENSE

MIT
