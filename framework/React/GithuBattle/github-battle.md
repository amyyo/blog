# Github Battle 第一个 React 实例
## 具备的基础知识
－ NPM
- Webpack
- First React Component (会写Hello World!)
## getting start 开始
- 安装环境
```sh
$ npm init -y
$ npm install --save react react-dom react-router && npm install --save-dev html-webpack-plugin webpack webpack-dev-server babel-{core,loader} babel-preset-{react,es2015,react-hmre}
```
## pure function, stateless component
使用纯函数渲染无状态的 `React` 组件。它不处理Ajax请求，只接收 状态(state)和属性(props)。
