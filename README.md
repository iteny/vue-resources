# vue-resources
####首先我们要安装node.js，如下我们配置一下vue2+webpack2
Notice: 执行下面的命令就在哪里创建node_modules目录,最好用VPN，否则就用淘宝镜像，这个时候非常重要打开音乐播放器，来一首24K Magic，轻松一下。
```
npm init -y //创建一个package.json的配置文件
npm install webpack-dev-server webpack vue-loader vue-style-loader vue-html-loader vue-hot-reload-api css-loader file-loader style-loader babel-runtime babel-preset-es2015 babel-plugin-transform-runtime babel-loader babel-core extract-text-webpack-plugin html-webpack-plugin --save-dev
npm install vue --save    //安装依赖
npm i expose-loader --save
