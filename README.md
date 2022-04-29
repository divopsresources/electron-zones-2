# Electron with Multi Next Instance

> Typescript

## Main at electron-next.ts

## Usage

```
yarn build-electron # 输出 main 文件夹
yarn dev:web
```

```
yarn build-electron # 输出 main 文件夹
yarn build:web
yarn start:web
```

https://github.com/zeit/next.js/tree/canary/examples/with-zones  
演示: https://with-zones.songlairui.now.sh/

## Next App

`<Link href='/site/B/path'/>` 需要改成 `<a href='/site/B/path'/>`

### Possible way

- 两个实例挂载在同一个 HTML 中，分别挂载 `#root_1` `#root_2`
- 实例允许嵌套, \_document.js 中嵌套两个实例
