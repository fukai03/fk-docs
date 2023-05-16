# fk-docx

A static site base on [dumi](https://d.umijs.org).

## Development

```bash
# install dependencies
$ pnpm install

# start dev server
$ pnpm start

# build docs
$ pnpm run build
```

## deploy on GitHub Pages

借助[gh-pages](https://github.com/tschaub/gh-pages)插件，可以将静态文件部署到 GitHub Pages 上。

```bash
npm install gh-pages --save-dev
# or
yarn add gh-pages -D
# or
pnpm add gh-pages -D
```

`package.json` 中添加

```json
"scripts": {
  "deploy": "gh-pages -d dist"
}
```

编译生成 `dist` 目录

```bash
# site 模版
npm run build

# react 模版
npm run docs:build
```

一键发布

```bash
npm run deploy
```

## LICENSE

MIT
