# sudoku-js
用于完成课程作业
##sudoku-cli
数独游戏客户端，游戏逻辑的判断
##sudoku-server
数独游戏服务器端实现用户的登录注册，记录分数和历史记录

###遇到的问题
 - 创建好index.js文件之后，使用node运行index.js
报错：
Error: Cannot find module 'is-generator-function'
原因：
直观原因是缺少依赖的包
解决办法：安装对应的插件即可
cnpm i is-generator-function -save
 - 虽然之前安装了koa但还是提示找不到koa
报错：
Error: Cannot find module 'koa'
原因：
直观原因是缺少依赖的包
解决办法：安装对应的插件即可
cnpm i koa -save