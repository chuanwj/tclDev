# tclDev

A script develop environment for IC industry.

Borrow the ideas from git flow, jsdoc and others to make IC script development easy. And engineers could focus on design issues.

## Why tcl

tcl is a script language which is widely used in IC industry.

So if use tcl script to show your idea, the idea could be used directly in EDA tool.

## Features

Features below have already been done. And I need to tidy the script and do the initial commit. If you have any suggestion and issues, please submit a issue of the repository.

 - 脚本管理，提供git快速建立脚本
 - 脚本开发和发布分离，自动获取依赖procedure
  * 支持自动发布shell下可执行脚本
  * 支持自动手册和演示文档生成，支持PDF/HTML/Markdown等格式，效果见[tclAutoDoc](https://github.com/xoit/tclAutoDoc "tclAutoDoc") 
  * 自动发布单个脚本或打包发布脚本package
 - 支持VimScript开发
 - 支持EDA工具中的man命令脚本
 - 集成某些工具和格式的使用和解析，如sdcparser，def/lef等
 - 集成常用unix工具配置，如vim, screen, tmux等
 - 集成perl常用module实例
 - 集成make等流程管理的实例
 - 集成Vim Script的实例

