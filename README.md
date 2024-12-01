# GTA5-Stand-LuaAIO

<p align="center">
  <a href="https://badges.toozhao.com/stats/01H69JD1N3ZWV3EDK36V3F5DJK"><img src="https://badges.toozhao.com/badges/01H69JD1N3ZWV3EDK36V3F5DJK/green.svg" /></a>
  <a href="https://discord.gg/wDcY8FFnt5"><img src="https://img.shields.io/discord/1167118210735276062?color=blue&label=discord&logo=discord&logoColor=white" /></a>
  <!-- <a href="http://qm.qq.com"><img src="https://img.shields.io/badge/QQ%E7%BE%A4-24242-blue" /></a> -->
  <img src="https://img.shields.io/github/license/xhcherry/GTA5-Stand-LuaAIO" />
</p>

[中文版本](https://github.com/xhcherry/GTA5-Stand-LuaAIO)/[English Version](https://github.com/xhcherry/GTA5-Stand-LuaAIO/tree/English)

<p align="center">
  GTA5 Mod Stand Lua All in One:将快捷任务、远程崩溃、模组(人物|车辆|地图|模型)、娱乐等多种standlua脚本于一体的综合库
</p>

# 目录

- [GTA5-Stand-LuaAIO](#gta5-stand-luaaio)
- [目录](#目录)
  - [合集优势](#合集优势)
  - [简易安装教程](#简易安装教程)
  - [一劳永逸安装教程](#一劳永逸安装教程)
  - [文件目录结构](#文件目录结构)
  - [仓库Lua二次开发指南](#仓库lua二次开发指南)
  - [贡献](#贡献)

## 合集优势

1.**核心优势** 可以通过此仓库体验到gt ultra功能和daidai ultimate功能\
2.免去单独下载每个lua的繁琐步骤，所有lua都已经拖入整个仓库，下载解压即可使用\
3.已提前下载了stand的所有库文件，在选择lua Scripts时将不会再弹出"请稍后"通知，可以打开任何lua无需等待

## 简易安装教程

[点击此处自动开始下载lua合集](https://github.com/xhcherry/GTA5-Stand-LuaAIO/archive/refs/heads/main.zip)\
等待下载完成后将下载的压缩包完全解压出来(**是解压出来，不是直接打开压缩包**)，将文件夹中的所有文件拖到Stand目录即可。\
**建议没有固定电脑玩游戏的玩家使用**，这需要频繁重新下载200多MB的压缩包并完全解压，很耗时间

## 一劳永逸安装教程

此教程会教你配置完整的仓库环境，以及克隆仓库的standlua至本地，使用此教程在日后的更新极其方便\
[一次性完成standlua合集仓库的配置教程](https://github.com/xhcherry/GTA5-Stand-LuaAIO/wiki/lua安装教程)\
**建议在固定电脑玩的玩家使用**，只有在第一次配置麻烦，在之后的仓库更新后，使用此教程的玩家只需要按四下就可以完成更新，并且更新很快，不用重新下载以及解压

## 文件目录结构

Lua Scripts：脚本目录：GRANDTOURINGVIP(ultra),Heist Control,daidai(ultimate)

Profiles：stand配置文件

多人任务：关闭了99%的通知以及保护，以确保在和朋友和联机游玩不出问题\
满防(不会触发自动反制)：此配置可以直接阻止大部分的负面反应，并通知\
满防(触发自动踢出)：此配置在阻止大部分的负面反应时会自动踢出攻击者(如果你的朋友用导弹或手雷炸你也会哦，慎用)，并通知

Theme：中文标签与主题文件

## 仓库Lua二次开发指南

对于想要了解统计数据、全局和局部变量或 Stand Lua Script API 的开发人员

Lua基础：[Lua基础教程](https://www.tutorialspoint.com/lua/index.htm)

pluto基础: [pluto](https://pluto-lang.org/)

学习stand lua API：[Stand Lua开发文档](https://stand.gg/help/lua-api-documentation)

游戏原生功能，两个地址一样的，哪个能访问就用哪个：
- [GTA5原生功能1](https://nativedb.dotindustries.dev/gta5/natives)
- [GTA5原生功能2](https://alloc8or.re/gta5/nativedb/)

控件、Blip等:[FiveM Docs-Game References](https://docs.fivem.net/docs/game-references/)

soup lua bindings：[soup lua bindings](https://github.com/calamity-inc/Soup-Lua-Bindings/blob/main/LUA_API.md#soup-lua-bindings)

查找统计数据、全局和局部变量:
- 常用freemode.c和tuneables_processing.c
- GTA 在线反编译脚本：https://github.com/root-cause/v-decompiled-scripts

## 贡献

参考此仓库[GTA-Stand-Lua-Scripts-Crack](https://github.com/zeblyo/GTA-Stand-Lua-Scripts-Crack)