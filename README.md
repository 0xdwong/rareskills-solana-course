# 60 Days of Solana Course By Rareskills 

本课程由 [RareSkills](https://www.rareskills.io/) 编写，DeCert.me 翻译为中文版，英文原版在[这里](https://www.rareskills.io/solana-tutorial)

本课程旨在帮助具有以太坊或 EVM 开发的初学者或中级背景的工程师快速掌握 Solana 程序开发

## 如何阅读本书

本书使用 mdBook 编写，你可以按照以下步骤下载、本地运行和部署在服务器上：

### 安装 mdBook

参照官网教程：[https://rust-lang.github.io/mdBook/guide/installation.html](https://rust-lang.github.io/mdBook/guide/installation.html)

### 在本地运行

1. 将本书的源代码克隆到本地：

    `git clone https://github.com/decert-me/rareskills-solana-course`

2. 进入项目目录：
    `cd rareskills-solana-course`

3. 运行以下命令以预览本书：
    `mdbook serve`

4. 打开浏览器，并访问 [http://localhost:3000](http://localhost:3000)，你将看到本书的预览版本

### 部署在服务器上

1. 构建本书静态页面：`mdbook build`
2. 整体将构建出来的`book`文件夹上传到服务器
2. 配置你的服务器以提供静态网页服务，例如使用 Nginx 或 Apache
3. 访问你配置的服务器地址，你将看到部署在服务器上的本书的正式版本