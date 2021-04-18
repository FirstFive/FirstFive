[<img width="134" src="https://vk.com/images/apps/mini_apps/vk_mini_apps_logo.svg">](https://vk.com/services)

# Ссылка на Figma (полная версия нашего приложения):
https://vk.com/away.php?to=https%3A%2F%2Fwww.figma.com%2Ffile%2F9QeXQZtPeF7v6t1zWtPnTq%2F%25D1%2585%25D0%25B0%25D1%2585%25D0%25B0%25D1%2582%25D0%25BE%25D0%25BD%3Fnode-id%3D0%253A1&cc_key=

# Create VK Mini App [![npm][npm]][npm-url] [![deps][deps]][deps-url]

## How to use

### With NPX

```bash
npx @vkontakte/create-vk-mini-app [app-directory-name] [options]
```
[NPX](https://github.com/npm/npx) allows you to always use the **latest** version of the package without a global installation.

### With installing the package globally
Install the package globally via yarn
```bash
yarn global add @vkontakte/create-vk-mini-app
```
...or npm
```bash
npm install --global @vkontakte/create-vk-mini-app
```

and use as follows

```bash
create-vk-mini-app [app-directory-name] [options]
```

This way is less recommended because you will have to update the package yourself.

### Options
Without `--zeit` and `--surge` options 

#### `--zeit`
Vercel (Zeit) deploy

Firstly, you have to create Vercel account and connect it with your GitHub profile on [vercel.com](https://vercel.com)

#### `--surge <surge-domain>`
Surge deploy

Firstly, you have to create Surge account and Surge-domain on [surge.sh](https://surge.sh)

#### `--help`
Prints the synopsis and a list of options

## How to start work with app

Go to created folder and run:  
`yarn start` or  `npm start` to start dev server with hot reload on `localhost:10888`.

`yarn run build` or `npm run build` to build production bundle, with tree-shaking, uglify and all this modern fancy stuff.

[npm]: https://img.shields.io/npm/v/@vkontakte/create-vk-mini-app.svg
[npm-url]: https://npmjs.com/package/@vkontakte/create-vk-mini-app

[deps]: https://img.shields.io/david/vkcom/create-vk-mini-app.svg
[deps-url]: https://david-dm.org/vkcom/create-vk-mini-app
