+++
title = "在 macOS 中安装SF Mono字体" # Title of the blog post.
date = 2021-02-28
description = "在 macOS 中安装SF Mono字体" # Description used for search engine.
featured = false 
toc =false
categories = [
  "macOS"
]

tags = [
  "Font"
]
+++

在 macOS 中，`SF Mono` 字体不是系统自带的字体，而是包含在`Terminal.app`中的字体，因为如果需要在其他的 App 使用到这个字体的话，就需要将这个`SF Mono`字体安装在系统当中。
<!--more-->

在`Catalina `macOS 系统当中，`SF Mono`字体的完整路径为：
```bash
/System/Applications/Utilities/Terminal.app/Contents/Resources/Fonts/
```
## 继续通过命令行方式安装字体
```bash
cp -R /System/Applications/Utilities/Terminal.app/Contents/Resources/Fonts/*.otf ~/Library/Fonts/
```
All done! 这样就可以在其他 App ，诸如`Visual Studio Code`中使用这个字体啦！