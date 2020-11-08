# webpack-first

## 如何用
1. 如果没有webpack.config.js配置文件，直接在命令行中输入   node_modules/.bin/webpack ./src/main.js -o common
2. 如果有webpack.config.js配置文件，直接在命令行中运行   webpack

## 为什么要使用webpack打包

## 如何使用webpack进行打包
### 最基本的使用方法
1. npm install webpack --save-dev // 项目内安装
（如果是webpack4，还需要安装webpack-cli，如果不安装的话，用webpack打包的时候，会提示你进行安装）
2. 执行命令：node_modules/.bin/webpack ./src/main.js -o common，即可进行webpack打包
### 添加webpack.config.js进行打包配置


----------
参考：https://www.jianshu.com/p/1192cfd4a012