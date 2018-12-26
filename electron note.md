新建一个electron 项目（前提：npm环境已经配置完成）
1.npm init
2.修改package json
"scripts": {
    "start": "node ."
 }
 修改为 "start": "electron ."
 
3.执行命令 npm install --save-dev electron
4.启动项目在根目录运行 npm start

