-----------old versions of Chrome apps won't open on Linux devices after December 2022---------

chrome app lan chat  基于浏览器插件的http服务器, 内网聊天工具, 同事间临时聊天, http server on chrome

把我改写的chrome_http_server.zip文件解压到一个文件夹(unzip chrome_http_server.zip -d chrome_http_server),

并在chrome浏览器的 chrome://extensions/ 页面 勾上 Developer mode,

然后Load unpacked extension 按钮选上前面解压的文件夹安装,

最后点击 Launch按钮(或从 chrome://apps/ )就启动了一个 http/websocket聊天服务器,

然后同事们都可以 访问 http://<我的内网ip>:21404 一起聊天了

如果运维有内网所有人名字 和 ip的对应关系 也可以很容易打包到 chrome http server里
