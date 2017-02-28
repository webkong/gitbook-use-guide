## 安装和基础使用

### 1. 基本依赖

* git

### 2.安装

* 官网下载并安装  [https://www.gitbook.com/editor](https://www.gitbook.com/editor)

* 打开客户端（可选登录gitbook或者不登录）

### 3.使用

* 点击 New Book 新建, 书写自己的内容    

* 在私有gitlab [http://192.168.255.50:8000/](http://192.168.255.50:8000/) 上注册

![](/assets/gitlab-register.png)

* 创建仓库

![](/assets/gitlab-new.png)

* 在终端(cmd/bash)找到新建Book的目录

```
win 一般在 C:\Users\{username}\GitBook\Library\Import
mac 一般在 /Users/{username}/GitBook/Library/Import 目录

```
* 在Book目录里执行命令

```
git config --global http.sslVerify false
git config --system http.sslVerify false
git remote add origin {http://192.168.255.50:8000/wangsw/test-gitbook.git}
// 关联到remote
```

* 在gitbook客户端修改内容都可以自动publish到git（第一次会输入用户名和密码）。

* git库和gitbook服务之间的钩子会根据新的提交来重新build成页面



