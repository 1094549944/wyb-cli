# wyb-cli
## 管理"项目脚手架"的脚手架工具

## 介绍

想象以下情景：
1. 当你使用vue-cli 或者 create-react-app 初始化项目后，是否仍需要自己封装一些方法，
修改项目目录结构等个性化配置以满足个人所需，当你重新初始化一个新的项目的时候是否需要重复执行以上步骤
2. 如果你通过模版封装解决了上述问题，是否遇到封装模版过多而导致混淆
3. 框架开发新手，想要站在"巨人的肩膀上"使用别人封装好的框架(todo)

如果你有上述问题之一，欢迎使用 ***wyb-cli*** 来管理你的众多脚手架。
## 安装

``` 
npm install -g wyb-cli 
```

## 基本功能

#### 1. 增加一个模版

```
wyb-cli add
```
#### 2. 删除一个模版
```$xslt
wyb-cli delete
```
#### 3.  展示所有模版

```$xslt
wyb-cli list
```
#### 4. 使用现有模版初始化项目
```$xslt
wyb-cli init
```
## TODO

1. 支持模糊查询已有模版
2. 优化展示UI界面，交互操作
3. 同步所有模版(共享)