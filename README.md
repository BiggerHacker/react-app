# 项目目录说明
```
.
+-- build

|   +-- webpack.config.js // webpack配置项

+-- src // 实际开发时客户端代码存放目录

|   +-- App.jsx // react组件

|   +-- index.js // 入口文件

+-- template

|   +-- index.html // 模板文件

+-- .babelrc // babel配置文件

+-- .eslintrc // eslint配置文件

+-- gitignore

+-- pageage.json

+-- yarn.lock
```

# 基于webpack配置的ES6+react组合开发
* ```git clone https://github.com/BiggerHacker/react-app.git``` 把项目clone到本地

* ```cd react-app``` 进入项目目录

* 运行命令 ```yarn install``` 安装项目依赖

* 接着输入 ```yarn start``` 热更新启动，打开浏览器输入```http://localhost:8888/```进入愉快的开发阶段吧！

* 项目打包 ```yarn build```

# 后续考虑用node中间层做服务端渲染，待定。。。
