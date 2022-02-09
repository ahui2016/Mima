# mima

Just another password manager.

本软件是一个有特色的密码管理器，既可架设到服务器中，也可在本地运行，通过访问网页使用（因此不同的电脑、手机系统都可使用，也不用考虑同步，这使得程序代码可以非常简单）。

采用简单有效的 NaCl (libsodium) 加密方式，该方式以 “容易正确处理” 为最大特点，
因此可以确保加密过程得到正确处理。


## Install (绿色软件，开箱即用)

本软件采用了 Go 语言的 embed 技术，把静态资源也打包到程序中，因此不需要安装，直接下载一个文件，通过点击或命令行启动程序，即可立即使用。

默认端口是 80, 启动程序后用浏览器访问 http://127.0.0.1 即可打开程序界面。

可使用 `-addr` 参数修改端口，例如:

```sh
mima.exe -addr 127.0.0.1:8080
```

## demo (在线演示)

https://mimademo.ai42.xyz


## 特点

- **完整的历史记录**（不仅记录历史密码，甚至用户名与备注的每次修改都全部记录）
- **神奇的标签功能**，利用标签可轻松实现多密码与分类，并可代替顶置（详见后文）
- **首页无列表**（多数密码管理软件一打开就是网址与用户名列表，虽然通常密码隐藏，但有时网址与用户名也可能是隐私，需要防旁人窥视）
