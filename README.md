
# HTTP/2 server for development

simplehttp2server：（仅开发环境使用）
----------------------------------------------

site：
* https://github.com/GoogleChrome/simplehttp2server

usage：
1. npm install simplehttp2server -g
2. 切换到项目，运行：simplehttp2server

ngrok：（有动态域名，可外网访问）
----------------------------------------------

site：
* https://ngrok.com/download

usage：
1. 切换到项目，运行：anywhere -p 8080
2. 切换到ngrok.exe，运行：ngrok http 8080

即：将localhost的服务代理到ngrok的https服务。

注意：端口可以任意，本地服务需与ngrok端口一致即可；
