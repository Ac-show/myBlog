### VUE打包后资源加载失败

在项目目录下创建vue.config.js文件

```js
module.exports = {
  publicPath: './'
}
```





### React打包后资源加载失败

在package.json中加入

```json
"homepage":"."
```

