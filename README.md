# RapidWechat
给自己~~开发~~随便弄的一个轻量级Linux版微信客户端
## 下载
[下载最新版本]
## 基于[electron]开发
[electron]大法好，~~有了electron，腰不酸了腿不痛了~~
## 使用方法
下载之后解压，然后双击rapidwechat就成了。
关闭的时候要先退出微信，才能关闭。(不会出现不小心关了还要重新扫码的~~事故~~了。)
## 安全
直接使用微信网页版进行封装，没有对数据传输做任何干预与处理，和使用网页版一样安全。
## 为啥要弄个这玩意？
Linux上总要打开浏览器，有时候不小心关了还要重新扫码太蛋疼了。
## 源码如何使用
##### 部署：
./rapidwechat文件夹下是代码，clone或者download之后进入该文件夹，下载[electron]
##### 运行：
```sh
npx electron .
```
##### 重新打包
请参考[electron]文档
## 已知问题
1不能正常收发表情包
2无法截图
3无法at人
这些先别提issue了

## 截图
扫码登录界面：
<p align="center">
  <img src="https://github.com/iBeiKeCyn/rapidwechat/blob/master/screenshot/pic.png?raw=true" alt="chat">
</p>
登录界面：
<p align="center">
  <img src="https://github.com/iBeiKeCyn/rapidwechat/blob/master/screenshot/login.png?raw=true" alt="chat">
</p>
聊天界面：
<p align="center">
  <img src="https://github.com/iBeiKeCyn/rapidwechat/blob/master/screenshot/chat.png?raw=true" alt="chat">
</p>
新消息提醒：
<p align="center">
  <img src="https://github.com/iBeiKeCyn/rapidwechat/blob/master/screenshot/notice.png?raw=true" alt="chat">
</p>




[下载最新版本]:  https://github.com/iBeiKeCyn/rapidwechat/releases
[electron]: https://github.com/electron/electron
