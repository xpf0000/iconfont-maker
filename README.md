# IconFont字体图标生成

## 配置

修改 src/gulpfile.js

```js
// 打包全部字体
const svgs = ['./svg/*.svg']

// 打包特定字体
// const svgs = [
//   './svg/addons.svg',
//   './svg/clean.svg'
// ]

// 字体className
const fontName = 'x-icon'
// 输出格式
const formats = ['ttf', 'eot', 'woff', 'woff2']
```

## 生成

```js
npm run build
```
