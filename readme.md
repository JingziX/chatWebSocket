使用nodejs+websocket做聊天界面
安装 nodejs-websocket
npm install nodejs-websocket

browser-sync:实时响应文件修改，浏览器同步刷新

安装全局
npm install -g browser-sync

启动
browser-sync start --server --files "*.css,*html"

git 仓库地址
git clone origin git@github.com:JingziX/chatWebSocket.git

启动后修改ws 为本地的ip地址

https://blog.csdn.net/CJXBShowZhouyujuan/article/details/77816944