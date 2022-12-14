# Xcode内置调试器：LLDB

* 最新版本：`v0.8`
* 更新时间：`20221104`

## 简介

介绍Xcode内置的调试器LLDB。先是LLDB概览；再详细介绍LLDB的命令，包括LLDB的命令概览和LLDB的各个命令；LLDB命令概览包括cheat sheet和help语法；LLDB常用命令包括image、register、expression，尤其是其中的p和po、memory、disassemble、thread、frame、breakpoint、watchpoint、以及调试控制相关的命令，包括run、continue、next和nexti、step和stepi、jump、finish、exit等，且都给出help语法和用法举例；然后再整理出相关心得，包括命令的缩写、Xcode中的lldb、iOS逆向、LLVM等等。最后给出相关的文档和资料。

## 源码+浏览+下载

本书的各种源码、在线浏览地址、多种格式文件下载如下：

### HonKit源码

* [crifan/xcode_debugger_lldb: Xcode内置调试器：LLDB](https://github.com/crifan/xcode_debugger_lldb)

#### 如何使用此HonKit源码去生成发布为电子书

详见：[crifan/honkit_template: demo how to use crifan honkit template and demo](https://github.com/crifan/honkit_template)

### 在线浏览

* [Xcode内置调试器：LLDB book.crifan.org](https://book.crifan.org/books/xcode_debugger_lldb/website)
* [Xcode内置调试器：LLDB crifan.github.io](https://crifan.github.io/xcode_debugger_lldb/website)

### 离线下载阅读

* [Xcode内置调试器：LLDB PDF](https://book.crifan.org/books/xcode_debugger_lldb/pdf/xcode_debugger_lldb.pdf)
* [Xcode内置调试器：LLDB ePub](https://book.crifan.org/books/xcode_debugger_lldb/epub/xcode_debugger_lldb.epub)
* [Xcode内置调试器：LLDB Mobi](https://book.crifan.org/books/xcode_debugger_lldb/mobi/xcode_debugger_lldb.mobi)

## 版权和用途说明

此电子书教程的全部内容，如无特别说明，均为本人原创。其中部分内容参考自网络，均已备注了出处。如发现有侵权，请通过邮箱联系我 `admin 艾特 crifan.com`，我会尽快删除。谢谢合作。

各种技术类教程，仅作为学习和研究使用。请勿用于任何非法用途。如有非法用途，均与本人无关。

## 鸣谢

感谢我的老婆**陈雪**的包容理解和悉心照料，才使得我`crifan`有更多精力去专注技术专研和整理归纳出这些电子书和技术教程，特此鸣谢。

## 更多其他电子书

本人`crifan`还写了其他`150+`本电子书教程，感兴趣可移步至：

[crifan/crifan_ebook_readme: Crifan的电子书的使用说明](https://github.com/crifan/crifan_ebook_readme)
