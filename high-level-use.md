## 高级应用

还有一个写更高端的应用技巧，比如说让渲染出来的html更漂亮，生成pdf等ebook，在文件中加搜索等，就需要在本地安装一个gitbook的服务。

以mac为例，不具配备win条件，win同学可按照步骤自行Google

### 1. 依赖

* Git
* Node
* NPM 
* NVM (可选)
* Python2.7.1以上
   
### 2. 安装gitbook和calibre组件

```bash
npm install gitbook-cli -g
```
calibre 是格式转换插件

[https://calibre-ebook.com](https://calibre-ebook.com)

或者linux使用命令

```
wget -nv -O- https://raw.githubusercontent.com/kovidgoyal/calibre/master/setup/linux-installer.py | python -c "import sys; main=lambda x:sys.stderr.write('Download failed\n'); exec(sys.stdin.read()); main('~/opt')"
```
'~/opt'是安装路径

mac先装好calibre.app再使用命令

```
sudo ln -s /Applications/calibre.app/Contents/MacOS/ebook-convert /usr/local/bin
```

安装成功后就可以使用 `gitbook [options] [command]` 来使用：

```
build [options] [source_dir] 根据文档目录构建书籍
serve [options] [source_dir] 构建并且提供书籍的 web 托管
install [options] [source_dir] 安装 GitBook 插件
pdf [options] [source_dir] 构建 pdf 格式的电子书
epub [options] [source_dir] 构建 ePub 格式的电子书
mobi [options] [source_dir] 构建 mobi 格式的电子书
init [source_dir]      根据 SUMARRY.md 文件的内容生成相应的目录和文件
publish [source_dir]   如果已绑定 GitBook.io，该命令可以直接发布书籍
git:remote [source_dir] [book_id] 为书籍设置远程 git 仓库

-h, --help     输出命令的使用说明
-V, --version  输出程序的版本号
```

可以不用客户端生成Book，可以通过命令`gitbook init`在任意文件夹生成Book


### 3. 安装插件

参考 [http://www.cnblogs.com/zhangjk1993/p/5066771.html](http://www.cnblogs.com/zhangjk1993/p/5066771.html)

















