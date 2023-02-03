#### Table of contents
**fork from https://github.com/lexkong**
```
-----------------------------------------------------
                                      __            
           __                  __    /\ \           
   __  __ /\_\    ___ ___     /\_\   \_\ \     __   
  /\ \/\ \\/\ \ /' __` __`\   \/\ \  /'_` \  /'__`\ 
  \ \ \_/ |\ \ \/\ \/\ \/\ \   \ \ \/\ \_\ \/\  __/ 
   \ \___/  \ \_\ \_\ \_\ \_\   \ \_\ \___,_\ \____\
    \/__/    \/_/\/_/\/_/\/_/    \/_/\/__,_ /\/____/

-----------------------------------------------------
```

* [vim IDE 部署](#vim-ide-部署)
	* [VIM IDE部署方法](#vim-ide部署方法)
	* [卸载](#卸载)
	* [IDE一览](#ide一览)
* Vim 功能 
    * [Vim 原生的功能](doc/vim.md)
    * [Vim IDE 功能](doc/ide.md)
    * [Vim 其他技巧](doc/skill.md)
* [vim版本发布](#vim版本发布)
* [小额捐款](#小额捐款)

> * VIM课外阅读--[笨方法学Vimscript](http://learnvimscriptthehardway.onefloweroneworld.com/)

## vim IDE 部署

### VIM IDE部署方法

> * 本 Vim 可以重复安装
> * 普通用户执行程序时需要有sudo权限

```
#git clone https://github.com/lexkong/lexVim.git
#chmod 777 -R Vim
#cd Vim
#./start_vim.sh
```
**部署中问题**

使用git clone失败

```
[root@localhost ~]# git clone https://github.com/lexkong/lexVim.git
Initialized empty Git repository in /root/Vim/.git/
error:  while accessing https://github.com/lexkong/lexVim.git/info/refs

fatal: HTTP request failed
```
解决方法
```
#git config --global http.sslVerify false
```

### 卸载
```
#cd ~
#rm -rf .vim*
```

### IDE一览

![Screenshot](https://github.com/lexkong/lexVim/blob/master/images/vim.jpg)

## vim版本发布 
----
* v1.0.7，2016-10-07，增加为 Markdown 生成 TOC 的 Vim 插件
* v1.0.5，2016-08-26，修正ctags,添加python 代码自动折叠
* v1.0.4，2016-05-29，添加自动生成markdown头信息
* v1.0.3，2016-05-18，对github文档进行整理
* v1.0.2，2014-08-13，新增：对Vim进行整理发布一键化程序 
* v1.0.1，2014-01-01，新增。发布初始版本。


## 小额捐款

如果你觉得Vim对你有帮助, 可以对作者进行小额捐款(微信):
    
![微信支付](https://github.com/lexkong/lexVim/blob/master/images/wechat.jpg)
