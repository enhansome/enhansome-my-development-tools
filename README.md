# Awesome ADoyle's Dev Toolbox with stars

ADoyle 的开发工具箱。持续更新中。<https://tools.adoyle.me>

These documents are written in Chinese. Please use your own translator to translate them into English.

推荐订阅 [Weekly Report](https://github.com/adoyle-h/my-development-tools/discussions/categories/weekly-report) ⭐ 479 | 🐛 0 | 🌐 SCSS | 📅 2026-07-30。每周一获取每周总结。
订阅方法：点击 [Github](https://github.com/adoyle-h/my-development-tools) ⭐ 479 | 🐛 0 | 🌐 SCSS | 📅 2026-07-30 右上角的 watch 按钮。

本文档只记录我在用的工具，所以

1. 不接受 Pull Request。有想法可以在 [Discussions](https://github.com/adoyle-h/my-development-tools/discussions) ⭐ 479 | 🐛 0 | 🌐 SCSS | 📅 2026-07-30 交流，或者发邮件给我。
2. 当我不用了或者找到更好的替代品，会移除旧记录。

在网页端，搜索英文建议用最上方的搜索框，体验比较好。
搜索框不支持中文，搜中文信息建议用浏览器自带的搜索功能。

## 版权声明 (Copyright and License)

Copyright 2016-2026 ADoyle (<adoyle.h@gmail.com>). Some Rights Reserved.
The project is licensed under the **BSD 3-clause License**.

Read the [LICENSE][] file for the specific language governing permissions and limitations under the License.

Read the [NOTICE][] file distributed with this work for additional information regarding copyright ownership.

## 说明

* `⨀` 表示 **开源软件**。本文档大部分都是开源的，所以只注明特别的软件；
* `Ⓜ` 表示兼容 **Mac 平台**；
* `Ⓛ` 表示兼容 **Linux 平台**；
* `ⓦ` 表示兼容 **Windows 平台**；
* `Ⓗ` 表示可以通过 [**Homebrew**](#Homebrew) 安装；
* `ⱳ` 表示 **Web 服务**；
* `ⓒ` 表示 Chrome 插件；

## TOC

<!-- <details close> -->

<!-- <summary>点击展开/折叠目录</summary> -->

<!-- MarkdownTOC GFM -->

* [其他](#其他)
  * [邮箱](#邮箱)
  * [养生](#养生)
  * [教你搜索](#教你搜索)
  * [历史遗珠](#历史遗珠)
  * [社区](#社区)
* [浏览器](#浏览器)
* [输入法](#输入法)
* [手册](#手册)
  * [Cheatsheet 管理器](#cheatsheet-管理器)
  * [Cheatsheet](#cheatsheet)
* [编译](#编译)
* [自动化](#自动化)
  * [CI/CD](#cicd)
  * [自动化构建](#自动化构建)
  * [自动化机器人](#自动化机器人)
* [财务](#财务)
* [短信](#短信)
* [统计数据](#统计数据)
  * [地理数据](#地理数据)
  * [网络数据](#网络数据)
* [伪数据](#伪数据)
* [政务信息](#政务信息)
* [法律](#法律)
* [数学](#数学)
* [桌面应用开发](#桌面应用开发)
* [Authentication](#authentication)
* [IAM](#iam)
* [Authorization](#authorization)
* [开源项目](#开源项目)
* [Ansible](#ansible)
* [Semver](#semver)
* [RFC](#rfc)
* [License](#license)
* [Github](#github)
* [SVG](#svg)
* [代码质量检查](#代码质量检查)
* [安全渗透](#安全渗透)
  * [IPS/IDS](#ipsids)
  * [网络威胁情报 CTI](#网络威胁情报-cti)
  * [蜜罐 Honeypot](#蜜罐-honeypot)
  * [密码](#密码)
  * [爆破字典](#爆破字典)
  * [社工库](#社工库)
  * [漏洞信息平台 CVE](#漏洞信息平台-cve)
  * [漏洞靶场](#漏洞靶场)
* [架构](#架构)
* [Checklist](#checklist)
* [编辑器/IDE](#编辑器ide)
  * [代码编辑器](#代码编辑器)
  * [富文本编辑器 WYSIWYG](#富文本编辑器-wysiwyg)
  * [Online IDE](#online-ide)
  * [IDE 辅助工具](#ide-辅助工具)
* [Telegram](#telegram)
* [下载工具](#下载工具)
* [终端 Terminal](#终端-terminal)
* [diff](#diff)
  * [image diff](#image-diff)
* [逆向工程](#逆向工程)
  * [二进制分析](#二进制分析)
* [结构化数据处理](#结构化数据处理)
  * [YAML](#yaml)
  * [HCL](#hcl)
  * [JSON](#json)
  * [JSON Schema](#json-schema)
  * [JSON Path](#json-path)
* [Lint](#lint)
* [Mock](#mock)
* [网站](#网站)
  * [访问统计](#访问统计)
* [SSL](#ssl)
* [BSD](#bsd)
* [Linux](#linux)
* [命令行 CLI](#命令行-cli)
* [Shell Script Development](#shell-script-development)
* [文件同步/备份/快照](#文件同步备份快照)
* [数据恢复](#数据恢复)
* [ISO 镜像制作与刻录](#iso-镜像制作与刻录)
* [数据库/存储](#数据库存储)
  * [Embeddable DB](#embeddable-db)
  * [数据库设计](#数据库设计)
  * [Database Versioning](#database-versioning)
* [网络](#网络)
* [ProtoBuf](#protobuf)
* [IM](#im)
* [Git](#git)
* [Chrome](#chrome)
* [Bookmarklet](#bookmarklet)
* [测试](#测试)
  * [字符串测试](#字符串测试)
  * [HTTP Benchmark](#http-benchmark)
  * [基准测试 (Benchmark Test)](#基准测试-benchmark-test)
  * [压测 (Stress Test)](#压测-stress-test)
* [密码相关](#密码相关)
  * [加密/解密](#加密解密)
  * [密码管理](#密码管理)
* [编码](#编码)
* [知识管理](#知识管理)
* [搜索引擎 Search Bar](#搜索引擎-search-bar)
  * [停止词 Stop Words](#停止词-stop-words)
* [邮件](#邮件)
* [翻译](#翻译)
* [Windows App](#windows-app)
* [Mac App](#mac-app)
* [字体](#字体)
* [Design](#design)
* [Emoji](#emoji)
* [Unicode](#unicode)
* [命名](#命名)
* [团队协作](#团队协作)
  * [即时通讯](#即时通讯)
* [ChatOps](#chatops)
* [电子书](#电子书)
  * [电子书阅读器](#电子书阅读器)
* [服务 (Service)](#服务-service)
  * [在线工具箱 (Online Toolbox)](#在线工具箱-online-toolbox)
  * [自部署的服务 (Self-Host Service)](#自部署的服务-self-host-service)
  * [定时任务](#定时任务)
  * [WAF](#waf)
  * [短链接](#短链接)
  * [评论系统](#评论系统)
  * [图床](#图床)
* [网盘](#网盘)
* [临时共享](#临时共享)
* [爬虫/Archive](#爬虫archive)
  * [爬虫代理池](#爬虫代理池)
* [静态文件服务](#静态文件服务)
* [文件管理服务](#文件管理服务)
* [静态文件托管](#静态文件托管)
* [CMS](#cms)
* [PaaS](#paas)
* [虚拟主机 (Web Hosting Account)](#虚拟主机-web-hosting-account)
* [Serverless](#serverless)
  * [Cloudflare](#cloudflare)
* [microVM](#microvm)
* [跳板机/堡垒机](#跳板机堡垒机)
* [REPL](#repl)
* [正则表达式 (Regex)](#正则表达式-regex)
* [语法分析/AST](#语法分析ast)
* [数据可视化](#数据可视化)
  * [地图](#地图)
* [日志](#日志)
* [交互式 Notebook](#交互式-notebook)
* [简历](#简历)
* [Zig](#zig)
* [Lua](#lua)
* [Python](#python)
* [Java](#java)
* [Golang](#golang)
* [NodeJS](#nodejs)
* [TypeScript](#typescript)
* [WebAssembly](#webassembly)
* [Nix](#nix)
* [前端开发](#前端开发)
* [Docker](#docker)
* [K8S/Kubernetes](#k8skubernetes)
* [硬件](#硬件)
* [HASS (Home Assistant)](#hass-home-assistant)
* [虚拟化](#虚拟化)
  * [libvirt/KVM](#libvirtkvm)
* [模板引擎](#模板引擎)
* [TeX/LaTeX](#texlatex)
* [Slide/Presentation](#slidepresentation)
* [SSG: Static Site Generator](#ssg-static-site-generator)
  * [JAMstack](#jamstack)
* [文档](#文档)
  * [文档系统](#文档系统)
  * [文档处理](#文档处理)
  * [文档检查](#文档检查)
  * [文档排版](#文档排版)
  * [Markdown](#markdown)
  * [Markdown 编辑器](#markdown-编辑器)
  * [Changelog](#changelog)
* [Hash](#hash)
* [图像处理](#图像处理)
* [视频处理](#视频处理)
* [压缩/解压](#压缩解压)
* [OCR](#ocr)
* [Android](#android)
* [截图/录屏](#截图录屏)
* [漫画](#漫画)
* [视频/音频](#视频音频)
  * [音乐](#音乐)
* [知识图谱](#知识图谱)
* [互联网关键词趋势](#互联网关键词趋势)
* [机器学习](#机器学习)
* [运营](#运营)
* [中国特色](#中国特色)
* [人文](#人文)
* [Funny](#funny)
* [游戏开发](#游戏开发)
* [二维码](#二维码)
* [FTP](#ftp)
* [资讯/信息](#资讯信息)
  * [RSS](#rss)
* [别人的工具列表](#别人的工具列表)

<!-- /MarkdownTOC -->

<!-- </details> -->

## 其他

* [Docker-OSX](https://github.com/sickcodes/Docker-OSX) ⭐ 52,900 | 🐛 418 | 🌐 Shell | 📅 2025-11-11: 在 Docker 里运行 MacOS
* [glance](https://github.com/glanceapp/glance) ⭐ 36,764 | 🐛 312 | 🌐 Go | 📅 2026-08-29: 用 YAML 配置的导航页。支持 RSS 展示，这个功能很棒。不支持热更新。插件略少。
* [etcher](https://github.com/resin-io/etcher) ⭐ 34,272 | 🐛 689 | 🌐 TypeScript | 📅 2026-06-02: 将系统镜像写入外接硬盘的工具
* [homepage](https://github.com/gethomepage/homepage) ⭐ 32,341 | 🐛 1 | 🌐 JavaScript | 📅 2026-09-01: 用 YAML 配置的导航首页。简单好用。
* [Bilibili-Evolved](https://github.com/the1812/Bilibili-Evolved) ⭐ 30,348 | 🐛 494 | 🌐 TypeScript | 📅 2026-08-23: 强大的哔哩哔哩油猴脚本
* [asdf](https://github.com/asdf-vm/asdf) ⭐ 25,561 | 🐛 151 | 🌐 Go | 📅 2026-08-28: 通用的程序版本管理工具。类似 gvm、nvm、rbenv，不过每种语言管理器作为 asdf plugin 使用。
* [OSX-KVM](https://github.com/kholia/OSX-KVM) ⭐ 23,606 | 🐛 21 | 🌐 Shell | 📅 2026-01-26: 在 KVM 里运行 MacOS
* [upx](https://github.com/upx/upx) ⭐ 17,826 | 🐛 24 | 🌐 C++ | 📅 2026-09-01: 压缩可执行文件
* [UnblockNeteaseMusic](https://github.com/nondanee/UnblockNeteaseMusic) ⭐ 17,357 | 🐛 219 | 🌐 JavaScript | 📅 2023-06-25: 解锁网易云音乐客户端变灰歌曲
  * [Listen 1](https://github.com/listen1/listen1_chrome_extension) ⭐ 12,081 | 🐛 448 | 🌐 JavaScript | 📅 2025-06-17
  * [ieaseMusic](https://github.com/trazyn/ieaseMusic) ⚠️ Archived
* [browserless](https://github.com/joelgriffith/browserless) ⭐ 13,651 | 🐛 12 | 🌐 TypeScript | 📅 2026-09-01: Chrome as a service in docker
* [plasmo](https://github.com/PlasmoHQ/plasmo) ⭐ 13,140 | 🐛 371 | 🌐 TypeScript | 📅 2026-08-31: 浏览器插件开发框架
* [franc](https://github.com/wooorm/franc) ⭐ 4,411 | 🐛 6 | 🌐 JavaScript | 📅 2024-06-12: 自然语言语种推测
* [screenFetch](https://github.com/KittyKatt/screenFetch) ⭐ 4,074 | 🐛 170 | 🌐 Shell | 📅 2026-03-02: 获取系统信息`Ⓛ` `Ⓜ`
  * [neofetch](https://github.com/dylanaraps/neofetch) ⚠️ Archived: 终端中打印系统信息，纯 Bash 实现。
* [insect](https://github.com/sharkdp/insect) ⚠️ Archived: 很不错的计算器，单位换算很方便。提供网页在线服务，也提供终端程序。开源。跨平台。
* [irssi](https://github.com/irssi/irssi) ⭐ 3,132 | 🐛 231 | 🌐 C | 📅 2026-02-01: IRC Client
* [go-musicfox](https://github.com/go-musicfox/go-musicfox) ⭐ 2,535 | 🐛 12 | 🌐 Go | 📅 2026-08-31: 在终端里听网易云音乐
* [wakeonlan](https://github.com/jpoliv/wakeonlan) ⭐ 421 | 🐛 11 | 🌐 Perl | 📅 2026-08-12: 网络唤醒工具
* [7zip](https://www.7-zip.org/): 免费开源的压缩软件。支持多种压缩算法、多种压缩等级、加密、分片。支持命令行和桌面端。
* <https://freedium.cfd/> : 阅读 Medium 的付费文章
* [pdfgear](https://www.pdfgear.com/): 阅读、编辑、转换、合并和跨设备签署 PDF 文件，完全免费无需注册。

### 邮箱

* <https://mail.proton.me/> : 注册步骤简单，无须电话和个人信息。注重用户隐私，公司总部位于瑞士。
* <https://mail.google.com/> : 注册步骤非常复杂。
* <https://outlook.live.com/> : 部分网站不接受用 outlook 邮箱注册账号。

### 养生

* [人体系统调优不完全指南](https://github.com/zijie0/HumanSystemOptimization) ⭐ 21,812 | 🐛 18 | 📅 2025-09-10

### 教你搜索

* <https://lmstfy.net/> : 帮你 google
* <https://letmegooglethat.com/> : 帮你 google
* <https://lmstfy.net/baidu/> : 帮你 baidu
* <https://lmstfy.net/bing/> : 帮你 bing

### 历史遗珠

那些有意义却不为众人所知或被众人遗忘的项目。

* [Sourcetrail](https://github.com/CoatiSoftware/Sourcetrail) ⚠️ Archived: 代码可视化浏览器
* [Plan 9](https://9p.io/plan9/)

### 社区

* [Tech Talks](https://github.com/just-talks/tech-talks) ⭐ 107 | 🐛 0 | 📅 2023-08-01: 纯技术交流的中文论坛。
* [V2EX](http://www.v2ex.com/): 创意工作者们的社区。

## 浏览器

* [neko](https://github.com/m1k1o/neko) ⭐ 22,223 | 🐛 149 | 🌐 Go | 📅 2026-08-30: 在容器里运行浏览器
* [Tor](https://www.torproject.org/): 专注于用户隐私的浏览器。需要翻墙

## 输入法

* [rime-ice 雾凇拼音](https://github.com/iDvel/rime-ice) ⭐ 19,120 | 🐛 5 | 🌐 Lua | 📅 2026-08-31: RIME 配置方案+词库，词库长期维护
* [小狼毫 Weasel](https://github.com/rime/weasel) ⭐ 7,907 | 🐛 258 | 🌐 C++ | 📅 2026-08-18: Rime for Windows，自带配置管理器，不用安装 plum。
* [鼠须管 squirrel](https://github.com/rime/squirrel) ⭐ 6,310 | 🐛 205 | 🌐 Swift | 📅 2026-08-13: Rime for MacOS
  * [Squirrel-Designer](https://github.com/LEOYoon-Tsaw/Squirrel-Designer) ⭐ 235 | 🐛 1 | 🌐 Swift | 📅 2026-06-12: 鼠须管皮肤制作工具
* [fcitx5-android](https://github.com/fcitx5-android/fcitx5-android) ⭐ 5,607 | 🐛 103 | 🌐 Kotlin | 📅 2026-08-25: 目前[不支持九宫格](https://github.com/fcitx5-android/fcitx5-android/issues/377) ⭐ 5,607 | 🐛 103 | 🌐 Kotlin | 📅 2026-08-25
* [同文输入法](https://github.com/osfans/trime) ⭐ 4,607 | 🐛 110 | 🌐 Kotlin | 📅 2026-09-01: Rime for Android
* [rime/plum](https://github.com/rime/plum) ⭐ 1,908 | 🐛 22 | 🌐 Shell | 📅 2026-05-08: RIME 的配置管理工具
* [Hamster](https://github.com/imfuxiao/Hamster) ⭐ 1,625 | 🐛 41 | 🌐 Swift | 📅 2025-05-13: Rime for iOS
* [fcitx-rime](https://github.com/fcitx/fcitx5-rime) ⭐ 424 | 🐛 5 | 🌐 C++ | 📅 2026-08-27: Rime for Linux
* [RIME](https://rime.im/download/): 开源输入法。支持 Windows/Mac/Linux/Android

## 手册

### Cheatsheet 管理器

* [tldr](https://github.com/tldr-pages/tldr/) ⭐ 63,551 | 🐛 309 | 🌐 Markdown | 📅 2026-09-01: 命令行工具，手册内容由社区维护，非常详尽。
* <http://devdocs.io/> : 社区维护内容。在线网页，也支持 PWA。[开源的](https://github.com/Thibaut/devdocs/) ⭐ 39,398 | 🐛 217 | 🌐 Ruby | 📅 2026-08-30
* [cheat](https://github.com/cheat/cheat) ⭐ 13,442 | 🐛 34 | 🌐 Go | 📅 2026-05-19: 命令行工具，本地存储，支持多 cheatsheets 扩展。这个仓库只有程序，需要下载官方 cheatsheets 配合使用。还可以 `cheat -e` 自己编辑维护。
  * [cheat/cheatsheets](https://github.com/cheat/cheatsheets) ⭐ 2,034 | 🐛 34 | 🌐 Shell | 📅 2024-08-06: 官方 cheatsheets
  * [adoyle-h/my-command-cheat](https://github.com/adoyle-h/my-command-cheat) ⭐ 4 | 🐛 0 | 📅 2024-10-04: 我的 cheatsheets
* [Dash](https://kapeli.com/dash): 桌面程序。Mac 专用。 `Ⓜ`
* [zealdocs](https://zealdocs.org/): 桌面程序。跨平台

### Cheatsheet

* [cheat.sh](https://github.com/chubin/cheat.sh) ⭐ 41,711 | 🐛 149 | 🌐 Python | 📅 2025-12-23: cheatsheet 服务，可通过 curl 获取内容，内容由社区维护。
* [Rico's cheatsheets](https://devhints.io): 网页版，[源码](https://github.com/rstacruz/cheatsheets) ⭐ 14,455 | 🐛 929 | 🌐 SCSS | 📅 2026-08-25
* [BASH CHEATSHEET (中文速查表) - by skywind](https://github.com/skywind3000/awesome-cheatsheets/blob/master/languages/bash.sh) ⭐ 12,562 | 🐛 24 | 🌐 Shell | 📅 2025-11-12
* <https://learnxinyminutes.com> : 快速学习各种编程语言的手册。[源码](https://github.com/adambard/learnxinyminutes-docs) ⭐ 12,339 | 🐛 240 | 🌐 Markdown | 📅 2026-08-21
* [linux-cheat](https://github.com/cirosantilli/linux-cheat) ⭐ 919 | 🐛 2 | 🌐 Shell | 📅 2019-04-16: Linux user-land CLI utilities
* [explainshell.com/](https://explainshell.com/): 形象解释 shell 命令
* [GNU Make Cheatsheet](https://gist.github.com/rueycheng/42e355d1480fd7a33ee81c866c7fdf78)
* [ANSI Escape Sequences](https://gist.github.com/fnky/458719343aabd01cfb17a3a4f7296797)

## 编译

* [llvm](https://llvm.org/)
* <https://godbolt.org/> : 在线预览汇编码的工具，支持各种版本和架构下的 clang，gcc，甚至还能查看 wasm 指令。

## 自动化

* [maestro](https://github.com/d-dev-inc/maestro): 使用声明式语法，在移动端执行自动化操作。

### CI/CD

* [drone](https://github.com/drone/drone) ⭐ 38,200 | 🐛 103 | 🌐 Go | 📅 2026-09-01: Drone is a Continuous Delivery platform built on Docker, written in Go
* [GoCD](https://github.com/gocd/gocd) ⭐ 7,434 | 🐛 82 | 🌐 Java | 📅 2026-09-01: written in java
* [Travis CI](https://github.com/marketplace/travis-ci/): 付费服务

### 自动化构建

* [justfile](https://github.com/casey/just) ⭐ 35,567 | 🐛 172 | 🌐 Rust | 📅 2026-08-20: 类似 makefile，但更好用
* [xmake](https://github.com/xmake-io/xmake) ⭐ 12,180 | 🐛 250 | 🌐 Lua | 📅 2026-08-31: 基于 Lua 的轻量级跨平台构建工具
* `make` 与 `makefile`: 缺点是不能跨平台，优点是能够直接调用 shell 命令和环境变量
  * [Makefile 简易教程](https://seisman.github.io/how-to-write-makefile/introduction.html)
* <https://danger.systems/> : code review 时挺有用的自动化工具
  * [danger-js](https://github.com/danger/danger-js) ⭐ 5,504 | 🐛 163 | 🌐 TypeScript | 📅 2026-08-28: JS 版本

### 自动化机器人

* [rasa](https://github.com/RasaHQ/rasa) ⭐ 21,308 | 🐛 153 | 🌐 Python | 📅 2026-07-24: 聊天机器人。Python 实现的。
* [hubot](https://github.com/github/hubot) ⭐ 16,798 | 🐛 6 | 🌐 JavaScript | 📅 2026-07-22: 交互机器人
* [botpress](https://github.com/botpress/botpress) ⭐ 14,884 | 🐛 52 | 🌐 TypeScript | 📅 2026-08-31: 聊天机器人。TS 实现的。
* [robotjs](https://github.com/octalmage/robotjs) ⭐ 12,772 | 🐛 7 | 🌐 C | 📅 2026-08-07: 用 NodeJS 定制 GUI 自动化流程。支持 Windows, Mac, Linux 系统
  * [nut.js](https://github.com/nut-tree/nut.js) ⭐ 2,849 | 🐛 43 | 🌐 TypeScript | 📅 2024-05-01: 备选方案

## 财务

* [beancount](https://github.com/beancount/beancount) ⭐ 5,958 | 🐛 238 | 🌐 Python | 📅 2026-08-23: 复式记账语言，纯文本编辑，命令行操作，提供类似 SQL 的查询
  * [ledger](https://github.com/ledger/ledger) ⭐ 6,024 | 🐛 19 | 🌐 C++ | 📅 2026-08-28: 备选方案
  * [参考](https://www.bmpi.dev/self/beancount-my-accounting-tool-v2/)
* [fava](https://github.com/beancount/fava) ⭐ 2,564 | 🐛 100 | 🌐 Python | 📅 2026-08-25: beancount 的 Web 界面
* [double-entry-generator](https://github.com/deb-sig/double-entry-generator) ⭐ 715 | 🐛 27 | 🌐 Go | 📅 2026-08-04: 根据支付宝、微信的账单生成 beancount 代码

## 短信

* [SmsForwarder](https://github.com/pppscn/SmsForwarder) ⭐ 27,789 | 🐛 10 | 🌐 Kotlin | 📅 2026-09-01: 短信转发器（安卓系统）
* 临时接收手机短信
  <!-- - https://sms-activate.org/ : 最靠谱的平台，价格不贵 -->
  <!-- - https://5sim.net/zh : 似乎挺便宜的 -->
  * <https://sms24.me/en/> (这个有中国号码，下面那些没有)
  * <https://jiemahao.com/>
  * <https://yunduanxin.net/Countries/>
  * <https://pingme.tel/receive-sms-online-cn/>

## 统计数据

* [国家统计局](http://www.stats.gov.cn/tjsj/)
* [国家能源局](http://www.nea.gov.cn/)
* [北京大学开放研究数据平台](https://opendata.pku.edu.cn/)
* [国家药品监督管理局](https://www.nmpa.gov.cn/datasearch/home-index.html)

### 地理数据

* <https://www.poi86.com/> : POI 数据

### 网络数据

## 伪数据

* <https://jsonplaceholder.typicode.com/>
* <http://dummy.restapiexample.com/>
* <https://mockae.com/> : 基于 db.json 和 lua 脚本构建 mock 服务器

## 政务信息

* [全国人大网](http://www.npc.gov.cn/)
* [互联网信息服务投诉平台](https://ts.isc.org.cn/#/complaint/default)

## 法律

知法才能避免犯法。写程序也容易违法。

* [中国法律检索系统](http://law.pkulaw.com/)

## 数学

* [中文数学 Wiki](https://math.fandom.com/zh/wiki/%E4%B8%AD%E6%96%87%E6%95%B0%E5%AD%A6_Wiki:%E4%B8%BB%E9%A1%B5)
* [3Blue1Brown](https://space.bilibili.com/88461692)

## 桌面应用开发

* [electron](https://github.com/electron/electron) ⭐ 122,834 | 🐛 745 | 🌐 C++ | 📅 2026-09-01: 用 Web 技术栈开发跨平台的桌面应用
* [tauri](https://github.com/tauri-apps/tauri) ⭐ 110,724 | 🐛 1,457 | 🌐 Rust | 📅 2026-09-01: 用 Web + Rust + JS 开发跨平台的桌面应用。Web 技术做窗口渲染，Rust 做后端引擎。linux 下使用 GTK + WebKitGTK，windows 使用 windows-rs + WebView2，MacOS 使用 AppKit + WKWebView。Android 和 iOS 的支持还在开发中。包大小、内存占用，都优于 electron。

## Authentication

* [2FAS](https://2fas.com/): 2FA 客户端，支持 iOS 和 Android。支持 TOTP 和 HOTP。用户体验好，功能丰富。开源。支持浏览器插件（同步需要翻墙）
* KeePass 也支持 2FA
* [otpauth](https://github.com/dim13/otpauth) ⭐ 951 | 🐛 6 | 🌐 Go | 📅 2026-07-30: 导出 Google Authenticator 里存储的数据

## IAM

* [authelia](https://github.com/authelia/authelia) ⭐ 28,762 | 🐛 123 | 🌐 Go | 📅 2026-09-01: 轻量级。支持 nginx 和 traefik。缺点是 Identity Provider 只支持 OpenID Connect 1.0。
* [authentik](https://github.com/goauthentik/authentik) ⭐ 25,300 | 🐛 1,083 | 🌐 Python | 📅 2026-09-01: 功能丰富但复杂，入门成本比较高。部署容易。UI 丑，但可以更换背景和 Logo，也可以自定义 CSS 来美化 UI。注意 license，不适合用在公司，适合个人使用。支持 nginx 和 traefik。缺点是 [domain-level forward auth 不支持权限控制](https://github.com/goauthentik/authentik/discussions/13823) ⭐ 25,300 | 🐛 1,083 | 🌐 Python | 📅 2026-09-01。
* [hydra](https://github.com/ory/hydra) ⭐ 17,512 | 🐛 95 | 🌐 Go | 📅 2026-07-29: OpenID Connect and OAuth Provider written in Go
  * [dex](https://github.com/dexidp/dex) ⭐ 11,077 | 🐛 536 | 🌐 Go | 📅 2026-08-31: 备选方案
* [zitadel](https://github.com/zitadel/zitadel) ⭐ 14,920 | 🐛 1,144 | 🌐 Go | 📅 2026-09-01: 商业公司使用注意：AGPL3-only 协议。
* [Casdoor](https://github.com/casdoor/casdoor) ⭐ 14,307 | 🐛 113 | 🌐 Go | 📅 2026-09-01: An open-source Agent-first Identity and Access Management (IAM) /LLM MCP & agent gateway and auth server with web UI supporting OpenClaw, MCP, OAuth, OIDC, SAML, CAS, LDAP, SCIM, WebAuthn, TOTP, MFA, Face ID, Google Workspace, Azure AD

## Authorization

* [casbin](https://github.com/casbin/casbin) ⭐ 20,365 | 🐛 41 | 🌐 Go | 📅 2026-08-21: 一个类库。通过设计 PERM 模型来控制认证策略。支持 ACL, RBAC, ABAC 等策略。支持主流语言。
* [Open Policy Agent](https://github.com/open-policy-agent/opa) ⭐ 12,184 | 🐛 332 | 🌐 Go | 📅 2026-09-01: general-purpose policy engine
* [kyverno](https://github.com/kyverno/kyverno) ⭐ 8,091 | 🐛 668 | 🌐 Go | 📅 2026-09-01: Kubernetes-native policy engine

## 开源项目

* 必读
  * <https://opensource.guide/>
* 如何选择 License
  * <https://choosealicense.com/>
* 如何写 Issue/PR Template
  * <https://github.com/stevemao/github-issue-templates> ⭐ 4,462 | 🐛 6 | 📅 2024-03-20
* 如何写 Code of Conduct
  * <https://www.contributor-covenant.org/>
* 如何写 Security Policy
  * <https://docs.github.com/en/free-pro-team@latest/github/managing-security-vulnerabilities/adding-a-security-policy-to-your-repository>
  * <https://tools.ietf.org/html/draft-foudil-securitytxt-10>

## [Ansible](./ansible.md)

## Semver

* [semver-tool](https://github.com/fsaintjacques/semver-tool) ⭐ 820 | 🐛 6 | 🌐 Shell | 📅 2023-02-15: 纯 Bash 实现的 Semver 可执行命令
* [semver-diff](https://github.com/sindresorhus/semver-diff) ⚠️ Archived: semver 比较
* <https://semver.npmjs.com/> : npm semver calculator
* [commitlint][]

## RFC

* <https://tools.ietf.org/> : 查看 IETF RFC 文档的工具。
* <https://www.rfc-editor.org/> : 查看 IETF RFC 文档的工具。
* Markdown 生成 RFC 文档的工具
  * <https://github.com/mmarkdown/mmark> ⭐ 512 | 🐛 5 | 🌐 Go | 📅 2026-04-19
  * <https://github.com/cabo/kramdown-rfc2629> ⭐ 241 | 🐛 94 | 🌐 XSLT | 📅 2026-08-27
  * 例子：<https://github.com/danyork/writing-internet-drafts-in-markdown> ⭐ 12 | 🐛 0 | 🌐 Makefile | 📅 2019-09-20

## License

* [scancode-toolkit](https://github.com/nexB/scancode-toolkit) ⭐ 2,615 | 🐛 1,677 | 🌐 Python | 📅 2026-08-31: detects licenses, copyrights, package manifests & dependencies and more by scanning code ... to discover and inventory open source and third-party packages used in your code.
* [LicenseFinder](https://github.com/pivotal/LicenseFinder) ⭐ 1,795 | 🐛 149 | 🌐 Ruby | 📅 2024-07-22: Find licenses for your project's dependencies.
* <https://spdx.org/licenses/>
  * [license-list-data](https://github.com/spdx/license-list-data) ⭐ 691 | 🐛 1 | 🌐 HTML | 📅 2026-08-27: Various data formats for the SPDX License List including RDFa, HTML, Text, and JSON
  * [spdx-license-list](https://github.com/sindresorhus/spdx-license-list) ⭐ 94 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-24: nodejs 包

## [Github](./github/README.md)

## SVG

* [dom-to-image](https://github.com/tsayen/dom-to-image) ⭐ 10,779 | 🐛 338 | 🌐 JavaScript | 📅 2024-04-08: DOM 树导出成 SVG 或 PNG 图片

## 代码质量检查

* [SonarQube](https://github.com/SonarSource/sonarqube) ⭐ 10,944 | 🐛 0 | 🌐 Java | 📅 2026-08-28: 「待评估」

## 安全渗透

* [Metasploit](https://github.com/rapid7/metasploit-framework) ⭐ 38,924 | 🐛 604 | 🌐 Ruby | 📅 2026-08-31
* [rustscan](https://github.com/RustScan/RustScan) ⭐ 20,344 | 🐛 61 | 🌐 Rust | 📅 2026-08-26: Scans all 65k ports in 3 seconds.
* [nmap](https://github.com/nmap/nmap) ⭐ 13,493 | 🐛 676 | 🌐 C | 📅 2026-08-31: 网络扫描工具
* [falco](https://github.com/falcosecurity/falco) ⭐ 9,321 | 🐛 65 | 🌐 C++ | 📅 2026-08-31: 「待评价」intrusion and abnormality detection for Cloud Native platforms such as Kubernetes, Mesosphere, and Cloud Foundry. Detect abnormal application behavior.
* [Scanners-Box](https://github.com/We5ter/Scanners-Box) ⭐ 9,031 | 🐛 1 | 📅 2026-08-12: 安全行业从业者自研开源扫描器合辑
* [Awesome-Redteam](https://github.com/Threekiii/Awesome-Redteam) ⭐ 4,319 | 🐛 2 | 🌐 Python | 📅 2026-06-23: 一个攻防知识仓库
* [Darkmoon](https://github.com/ASCIT31/Dark-Moon) ⭐ 884 | 🐛 2 | 🌐 Python | 📅 2026-08-29: 开源（GPL-3.0）自主式 AI 渗透测试平台，覆盖 Web、API、Active Directory 与 Kubernetes，并可作为 MCP 主机。
* [Kali Linux](https://www.kali.org/)
  * [Kali Docker Image](https://hub.docker.com/r/kalilinux/kali-linux-docker): [参考资料](https://archive.ph/zh0wk)
* [Snyk](https://snyk.io/): 开源风险收集检测服务。提供 API 和 CLI 做检查。
* [Tiger](https://www.nongnu.org/tiger/): The Unix security audit and intrusion detection tool

### IPS/IDS

IDS（Intrusion Detection System，入侵检测系统）和 IPS（Intrusion Prevention System，入侵防御系统）本质上都属于网络安全里的检测/防护设备，区别核心在于：IDS 发现攻击，但通常不主动拦截。IPS 发现攻击，并且可以主动阻断。

* [fail2ban](https://github.com/fail2ban/fail2ban) ⭐ 18,518 | 🐛 271 | 🌐 Python | 📅 2026-08-26: 监控系统日志并自动封禁表现出恶意行为的主机 IP。它通过分析登录失败等日志模式，动态更新防火墙规则，以抵御暴力破解和其他自动化攻击。
* [CrowdSec](https://github.com/crowdsecurity/crowdsec) ⭐ 14,702 | 🐛 290 | 🌐 Go | 📅 2026-08-31: security solution offering crowdsourced protection against malicious IPs and access to the most advanced real-world CTI.

### 网络威胁情报 CTI

* <https://threathive.net/> : ThreatHive aggregates trusted open-source feeds and real-world honeypot data to produce a high-confidence blocklist.
* <https://www.abuseipdb.com/>
* <https://www.spamhaus.org/blocklists/>
  * <https://www.spamhaus.org/blocklists/spamhaus-blocklist/>
  * <https://www.spamhaus.org/blocklists/do-not-route-or-peer/>

### 蜜罐 Honeypot

* <https://github.com/paralax/awesome-honeypots/> ⭐ 10,540 | 🐛 23 | 🌐 Python | 📅 2026-06-01

### 密码

* [gitleaks](https://github.com/gitleaks/gitleaks) ⭐ 29,047 | 🐛 472 | 🌐 Go | 📅 2026-08-26: 检测 git 提交历史是否存在密码泄露
* [hashcat](https://github.com/hashcat/hashcat) ⭐ 26,672 | 🐛 356 | 🌐 C | 📅 2026-08-31: 很快的密码破解工具
* [John the Ripper jumbo](https://github.com/openwall/john) ⭐ 13,573 | 🐛 513 | 🌐 C | 📅 2026-08-01: mac 用户用 `brew install john-jumbo` 安装，不要安装 `brew install john`，前者有更多功能。

### 爆破字典

* <https://github.com/berzerk0/Probable-Wordlists> ⭐ 9,334 | 🐛 21 | 📅 2023-10-04
* <https://github.com/TheKingOfDuck/fuzzDicts> ⭐ 8,425 | 🐛 0 | 🌐 Python | 📅 2023-11-13
* <https://github.com/rootphantomer/Blasting_dictionary> ⭐ 5,286 | 🐛 0 | 🌐 Python | 📅 2022-03-21
* [pydictor](https://github.com/LandGrey/pydictor) ⭐ 3,652 | 🐛 13 | 🌐 Python | 📅 2024-12-05: 字典生成工具
* <https://github.com/jeanphorn/wordlist> ⭐ 1,802 | 🐛 2 | 🌐 Python | 📅 2026-04-28
* <https://github.com/zxcvbn001/password_brute_dictionary> ⭐ 1,325 | 🐛 0 | 🌐 Python | 📅 2021-10-08
* <https://github.com/shadowabi/S-BlastingDictionary> ⭐ 668 | 🐛 2 | 📅 2024-06-09

### 社工库

* [暗精灵社工库](https://t.me/AJL01_bot?start=9Vd56q8uTa)
* [TGsgkbot](https://t.me/SGKmainNEWbot?start=IVT62B06286)
* [sgk520\_bot](https://t.me/sgk520_bot?start=DMT534Ai5D)

### 漏洞信息平台 CVE

* <https://nvd.nist.gov/>
* <https://www.cvedetails.com/>
  * <https://cve.mitre.org/>
* [中国信息安全漏洞库](https://www.cnnvd.org.cn/)
  * [中国信息安全漏洞共享平台](https://www.cnvd.org.cn/)
* <https://www.cve.org/>
* [GitHub Security Lab](https://securitylab.github.com/)
* <https://www.exploit-db.com/>

### 漏洞靶场

* <https://github.com/vulhub/vulhub> ⭐ 21,188 | 🐛 52 | 🌐 Dockerfile | 📅 2026-07-22
* <https://github.com/Medicean/VulApps> ⚠️ Archived

## 架构

* [Microsoft Azure - 云设计模式](https://docs.microsoft.com/zh-cn/azure/architecture/patterns/)
  * [Github 仓库](https://github.com/mspnp/architecture-center) ⭐ 2,019 | 🐛 0 | 🌐 PowerShell | 📅 2026-09-01，[中文仓库](https://github.com/mspnp/architecture-center.zh-cn)
* <https://www.12factor.net/>
* <https://c4model.com/> : C4 Model 绘制架构图的方法论
  * <https://www.infoq.cn/article/C4-architecture-model>
  * [软件架构图的艺术](https://www.infoq.cn/article/crafting-architectural-diagrams)

## Checklist

* [Serverside Checklist](https://github.com/mtdvio/going-to-production/blob/master/serverside-checklist.md) ⭐ 1,452 | 🐛 1 | 📅 2017-12-10
* [SPA Checklist](https://github.com/mtdvio/going-to-production/blob/master/spa-checklist.md) ⭐ 1,452 | 🐛 1 | 📅 2017-12-10

## 编辑器/IDE

* [Visual Studio Code](https://github.com/Microsoft/vscode) ⭐ 190,361 | 🐛 20,342 | 🌐 TypeScript | 📅 2026-09-01: 可能是最棒的开源 IDE
  * [code-server](https://github.com/cdr/code-server) ⭐ 79,149 | 🐛 150 | 🌐 TypeScript | 📅 2026-08-27: Run VS Code on a remote server
  * [code-settings-sync](https://github.com/shanalikhan/code-settings-sync) ⭐ 4,089 | 🐛 298 | 🌐 TypeScript | 📅 2024-12-13: VSC 设置备份同步工具
* [neovim](https://github.com/neovim/neovim) ⭐ 102,057 | 🐛 1,864 | 🌐 Vim Script | 📅 2026-09-01: 终端编辑器，用 Python 写的 vim
  * [awesome-neovim](https://github.com/rockerBOO/awesome-neovim) ⭐ 21,339 | 🐛 6 | 🌐 Shell | 📅 2026-09-01
  * [oni](https://github.com/onivim/oni) ⚠️ Archived: Neovim GUI 编辑器
  * [nvim-lua-guide](https://github.com/nanotee/nvim-lua-guide) ⚠️ Archived: nvim 编程圣经
  * [vimspector](https://github.com/puremourning/vimspector) ⭐ 4,318 | 🐛 42 | 🌐 Vim Script | 📅 2026-08-31: A multi-language debugging system for Vim
  * [one.nvim](https://github.com/adoyle-h/one.nvim) ⭐ 187 | 🐛 0 | 🌐 Lua | 📅 2026-04-24: All-in-one neovim config framework in Lua.
  * [vim colors chemes](https://vimcolorschemes.com/)
* [micro](https://github.com/micro-editor/MICRO) ⭐ 29,486 | 🐛 971 | 🌐 Go | 📅 2026-09-01: 学习成本低，零配置的终端编辑器
* vim
  * [vim-fast](https://github.com/chenxuan520/vim-fast) ⭐ 102 | 🐛 1 | 🌐 Vim Script | 📅 2026-03-21: 提供了无插件的 vim 配置。（待评测）
* [Sublime](http://www.sublimetext.com): 也许现在比不上其他工具，它是推动编辑器体验进化的功臣。

### 代码编辑器

* [Monaco Editor](https://github.com/Microsoft/monaco-editor) ⭐ 46,632 | 🐛 848 | 🌐 JavaScript | 📅 2026-08-27: VS Code 的代码编辑器
* [ace](https://github.com/ajaxorg/ace) ⭐ 27,147 | 🐛 140 | 🌐 JavaScript | 📅 2026-08-13
* [CodeMirror](https://github.com/codemirror/dev/) ⚠️ Archived

### 富文本编辑器 WYSIWYG

* [editor.js](https://github.com/codex-team/editor.js) ⭐ 31,921 | 🐛 701 | 🌐 TypeScript | 📅 2026-08-31: A block-styled editor with clean JSON output
* [slate](https://github.com/ianstormtaylor/slate) ⭐ 31,756 | 🐛 652 | 🌐 TypeScript | 📅 2026-08-26
* [lexical](https://github.com/facebook/lexical) ⭐ 23,815 | 🐛 290 | 🌐 TypeScript | 📅 2026-09-01: facebook 出品
* [trix](https://github.com/basecamp/trix) ⭐ 20,008 | 🐛 184 | 🌐 JavaScript | 📅 2026-09-01
* [plate](https://github.com/udecode/plate) ⭐ 16,549 | 🐛 15 | 🌐 TypeScript | 📅 2026-09-01: The rich-text editor for React.
* [ory/editor](https://github.com/ory/editor) ⭐ 9,544 | 🐛 11 | 🌐 TypeScript | 📅 2026-07-28: 基于 React 和 Redux 的内容编辑器

### Online IDE

* [code-server](https://github.com/coder/code-server) ⭐ 79,149 | 🐛 150 | 🌐 TypeScript | 📅 2026-08-27: VSCode in the browser
* [Theia](https://github.com/theia-ide/theia) ⭐ 21,668 | 🐛 1,505 | 🌐 TypeScript | 📅 2026-09-01: Web IDE
* [gitpod](https://github.com/gitpod-io/gitpod) ⭐ 13,760 | 🐛 452 | 🌐 TypeScript | 📅 2026-08-31: VSCode in the browser + workspace
* [Codesandbox](https://github.com/CompuIves/codesandbox-client) ⭐ 13,638 | 🐛 613 | 🌐 JavaScript | 📅 2026-08-25
* [Eclipse Che](https://github.com/eclipse/che/) ⭐ 7,161 | 🐛 215 | 🌐 TypeScript | 📅 2026-08-27: 很不错的云端 IDE
* [codepan](https://github.com/egoist/codepan) ⭐ 1,204 | 🐛 68 | 🌐 JavaScript | 📅 2024-08-14: Like codepen and jsbin but works offline. <https://codepan.net>
* <https://stackblitz.com/> : StackBlitz, Online IDE powered by Visual Studio Code
  * [源码](https://github.com/stackblitz/core) ⭐ 10,879 | 🐛 834 | 📅 2024-06-09
* <https://codeanywhere.com/>

### IDE 辅助工具

* [TabNine](https://github.com/zxqfl/TabNine/) ⭐ 10,774 | 🐛 0 | 🌐 Shell | 📅 2025-09-04: 用深度学习进行自动补全。支持 VS Code, Sublime Text, Vim, Atom, Emacs
  * [GitHub Copilot](https://copilot.github.com/): 同上
* [universal-ctags](https://github.com/universal-ctags/ctags) ⭐ 7,271 | 🐛 260 | 🌐 C | 📅 2026-08-31: Universal-ctags 是 Darren Hiebert 的 Exuberant-ctags 的继任
* [PacVim](https://github.com/jmoon018/PacVim) ⭐ 3,329 | 🐛 22 | 🌐 C++ | 📅 2024-03-23: 用游戏教你学 VIM
* [NerdFonts](https://www.nerdfonts.com) 与 [cheat-sheet](https://www.nerdfonts.com/cheat-sheet): 程序员必备字体
  * [nerdfix](https://github.com/loichyan/nerdfix) ⭐ 471 | 🐛 2 | 🌐 Rust | 📅 2024-11-23: nerdfonts 升级用的工具

## [Telegram](./telegram/README.md)

## 下载工具

* [Motrix](https://github.com/agalwood/Motrix) ⭐ 54,936 | 🐛 133 | 🌐 TypeScript | 📅 2026-08-31: 美观又强大的下载工具（目前没人维护，[作者创业中](https://github.com/agalwood/Motrix/issues/1396) ⭐ 54,936 | 🐛 133 | 🌐 TypeScript | 📅 2026-08-31）
* [cobalt](https://github.com/imputnet/cobalt) ⭐ 42,531 | 🐛 267 | 🌐 Svelte | 📅 2026-04-06: 开源的下载视音频网站资源的工具「待评价」
* [aria2](https://github.com/aria2/aria2) ⭐ 41,888 | 🐛 1,175 | 🌐 C++ | 📅 2026-06-25: 最强大的下载工具
  * [AriaNg](https://github.com/mayswind/AriaNg) ⭐ 13,177 | 🐛 21 | 🌐 JavaScript | 📅 2026-06-21: aria2 的前端界面
  * [P3TERX/aria2.conf](https://github.com/P3TERX/aria2.conf) ⭐ 3,437 | 🐛 12 | 🌐 Shell | 📅 2024-02-28: aria2 参考配置
  * [aria2-in-container](https://github.com/adoyle-h/aria2-in-container) ⭐ 0 | 🐛 0 | 🌐 Dockerfile | 📅 2024-02-29: aria2 + ariang 的 Docker 镜像
* bt tracker: BT 下载必须设置 tracker，否则没有速度。
  * <https://github.com/ngosang/trackerslist> ⭐ 55,009 | 🐛 12 | 📅 2026-08-31
  * <https://github.com/XIU2/TrackersListCollection> ⭐ 32,066 | 🐛 1 | 📅 2026-09-01
* <https://y2meta.app/> : Youtube 下载工具，在线服务。支持 1080p，没广告，没套路，下载速度很快
  * [youtube-dl](https://github.com/rg3/youtube-dl) ⭐ 141,072 | 🐛 4,127 | 🌐 Python | 📅 2026-02-19: 开源的视频下载工具，命令行操作
  * <https://snapsave.io/> : 备选方案，在线服务
* <https://downsub.com/> : Youtube 字幕下载，支持各种语言以及双语字幕
* <https://bilibili.iiilab.com/> : 下载 B 站视频，需要关注微信公众号
  * [BBDown](https://github.com/nilaoda/BBDown) ⚠️ Archived: 开源的 B 站视频命令行下载工具
* <https://twitter.iiilab.com/> : 下载 Twitter 视频/照片，需要关注微信公众号
  * <https://www.downloadtwittervideo.com/> : 需要翻墙
* <https://instagram.iiilab.com/> : 下载 Instagram 视频/照片，需要关注微信公众号
* <https://yunyinyue.iiilab.com/> : 下载网易云音乐的歌，需要关注微信公众号

## 终端 Terminal

* [Windows Terminal](https://github.com/microsoft/terminal) ⭐ 104,772 | 🐛 1,762 | 🌐 C++ | 📅 2026-09-01: Windows 系统，推荐用这个终端 `ⓦ`
  * [cmder](https://github.com/cmderdev/cmder) ⭐ 27,003 | 🐛 67 | 🌐 PowerShell | 📅 2026-08-31: 备选方案
* [tabby](https://github.com/Eugeny/tabby) ⭐ 74,261 | 🐛 2,874 | 🌐 TypeScript | 📅 2026-08-31: 前端技术栈做的终端，可以用 CSS 定制界面，功能完善，支持 Windows/MacOS/Linux。注意：关闭「输入时滚动」选项，否则很容易屏幕闪烁。缺点：无法输入中文标点。
* [edex-ui](https://github.com/GitSquared/edex-ui) ⚠️ Archived: 非常酷！
* [Hyper](https://github.com/zeit/hyper) ⭐ 44,712 | 🐛 1,046 | 🌐 TypeScript | 📅 2026-08-21: 用前端技术栈做的终端。非常酷炫 `⨀`
  * [awesome-hyper](https://github.com/bnb/awesome-hyper) ⭐ 11,000 | 🐛 23 | 📅 2022-09-20
* [xterm.js](https://github.com/xtermjs/xterm.js) ⭐ 21,118 | 🐛 234 | 🌐 TypeScript | 📅 2026-09-01: A terminal for the web
* [iTerm2](https://www.iterm2.com): Mac 系统专用的终端，功能丰富，稳定 `Ⓜ`
* [Ghostty](https://ghostty.org/): 零配置、跨平台、开箱即用的终端
* [Wave](https://www.waveterm.dev/): 集成 AI、文件浏览器、网页浏览器的终端。开源、跨平台。**缺点：无法输入中文标点。**
* [warp](https://www.warp.dev/): 集成 AI 的终端，挺有意思的。缺点也很明显，必须用它这一套，不兼容 tmux。PS1 被强制替换掉了，跟其他软件不好配合。
* [cathode](https://itunes.apple.com/us/app/cathode/id656982811): 复古终端模拟器 `Ⓜ`

## diff

* [delta](https://github.com/dandavison/delta) ⭐ 32,049 | 🐛 433 | 🌐 Rust | 📅 2026-08-02: 语义化 Diff，功能丰富。Git 配置不友好。支持双列、git blame、git grep。
  * [difftastic](https://github.com/Wilfred/difftastic) ⭐ 25,847 | 🐛 296 | 🌐 Rust | 📅 2026-08-28: 基于 tree-sitter 的 diff。Git 配置不友好
  * [diff-so-fancy](https://github.com/so-fancy/diff-so-fancy) ⭐ 18,084 | 🐛 4 | 🌐 Perl | 📅 2026-08-31: 备选方案。diff 文件内容的着色增强工具，不支持语义化 diff。不支持双列 (side-by-side)。
* [diff2html-cli](https://github.com/rtfpessoa/diff2html-cli) ⭐ 602 | 🐛 16 | 🌐 TypeScript | 📅 2026-02-06: 将 diff 文件转成 HTML 页面的形式预览。非常漂亮
  * <https://diffy.org/> : 在线服务，支持链接共享。
* diff: linux 内置命令
* diffstat: linux 内置命令 `diff -u | diffstat -C`
* [Kaleidoscope](https://kaleidoscope.app/): Diff GUI 软件。支持比较文本、图片、目录。只支持 MacOS。
* [Meld](https://meldmerge.org/): Diff GUI 软件。支持比较文本、目录。支持 Linux/Unix/Windows，不支持 MacOS。

### image diff

* [pixelmatch](https://github.com/mapbox/pixelmatch) ⭐ 6,936 | 🐛 15 | 🌐 JavaScript | 📅 2026-07-07
  * [image-diff](https://github.com/uber-archive/image-diff) ⚠️ Archived
* <https://www.diffchecker.com/image-diff/> : 在线服务，图片 diff

## 逆向工程

### 二进制分析

* [Ghidra](https://github.com/NationalSecurityAgency/ghidra) ⭐ 74,188 | 🐛 1,924 | 🌐 Java | 📅 2026-08-31: 美国国家安全局开源的逆向工程框架
* [radare2](https://github.com/radareorg/radare2) ⭐ 24,697 | 🐛 819 | 🌐 C | 📅 2026-09-01: 逆向解析二进制文件的命令行工具集
  * [iaito](https://github.com/radareorg/iaito) ⭐ 1,693 | 🐛 7 | 🌐 C++ | 📅 2026-08-30: radare2 的 GUI 工具。跨平台，功能非常强大。ARM 架构的 MacOS 需要自己编译，很简单的。
  * [Radare2 official book](https://book.rada.re/)
* [binwalk](https://github.com/ReFirmLabs/binwalk) ⭐ 14,295 | 🐛 93 | 🌐 Rust | 📅 2026-08-11: 固件分析工具。
* [kaitai](https://github.com/kaitai-io/kaitai_struct) ⭐ 4,668 | 🐛 529 | 🌐 Shell | 📅 2026-08-31: 可以用 YAML 描述二进制文件的格式，从而解析二进制文件提取出自己想要的信息。它根据 YAML 生成各种语言的库。
  * <https://kaitai.io/>
  * 有很多[应用场景](https://formats.kaitai.io/)。模型，归档文件，安装包，文件系统，字体，图片，数据库，日志，网络协议。
  * Web IDE：<https://ide.kaitai.io/>
* [protobuf-inspector](https://github.com/mildsunrise/protobuf-inspector) ⭐ 1,126 | 🐛 5 | 🌐 Python | 📅 2020-12-13: 逆向解析 protobuf

## 结构化数据处理

* [miller](https://github.com/johnkerl/miller) ⭐ 10,006 | 🐛 70 | 📅 2026-09-01: 「待评价，看起来参数很复杂」like awk, sed, cut, join, and sort for data formats such as CSV, TSV, JSON, JSON Lines, and positionally-indexed.
* [dasel](https://github.com/TomWright/dasel) ⭐ 8,030 | 🐛 25 | 🌐 Go | 📅 2026-08-16: JSON, TOML, YAML, XML, CSV 增删改查、格式转换工具。缺点：无法直接 put 数组。
* [Structured text tools](https://github.com/dbohdan/structured-text-tools) ⭐ 7,145 | 🐛 6 | 📅 2026-08-12
* [Awesome JSON - What's Next?](https://github.com/json-next/awesome-json-next) ⭐ 70 | 🐛 1 | 📅 2021-02-23
* 我喜欢的面向人类的配置文件语法
  * [TOML](https://github.com/toml-lang/toml) ⭐ 20,600 | 🐛 8 | 📅 2026-08-30
  * [HCL](https://github.com/hashicorp/hcl) ⭐ 5,801 | 🐛 236 | 🌐 Go | 📅 2026-08-27: 类似 Nginx 的语法配置，Hashicorp 出品
  * [YAML](http://yaml.org/)
  * [INI](https://www.wikiwand.com/zh-hans/INI%E6%96%87%E4%BB%B6)
* 面向机器数据结构语法
  * JSON

### YAML

* [yq](https://github.com/mikefarah/yq) ⭐ 15,910 | 🐛 291 | 🌐 Go | 📅 2026-08-27: 类似 jq
* [yaml-sucks](https://github.com/cblp/yaml-sucks) ⭐ 657 | 🐛 4 | 🌐 Shell | 📅 2024-12-12: YAML 的缺点列表
* <http://yaml-online-parser.appspot.com/>
* [yamline](https://yamline.com/): 在线 YAML 工具

### HCL

* <https://www.hcl2json.com/> : 需要翻墙

### JSON

* [simdjson](https://github.com/lemire/simdjson) ⭐ 24,220 | 🐛 135 | 🌐 C++ | 📅 2026-08-31: Parsing gigabytes of JSON. 2.2GB/s
* [fx](https://github.com/antonmedv/fx) ⭐ 20,617 | 🐛 27 | 🌐 Go | 📅 2026-08-26: JSON Viewer，体验最好
  * [jq](https://github.com/stedolan/jq) ⭐ 35,526 | 🐛 474 | 🌐 C | 📅 2026-09-01: JSON Viewer，命令行，无交互
  * [jid](https://github.com/simeji/jid) ⭐ 7,136 | 🐛 10 | 🌐 Go | 📅 2026-08-02: 交互式 JSON Viewer
  * [jless](https://github.com/PaulJuliusMartinez/jless) ⭐ 5,471 | 🐛 94 | 🌐 Rust | 📅 2026-08-25: 类似 fx。备选方案。
  * [jiq](https://github.com/fiatjaf/jiq) ⚠️ Archived: It's jid with jq.
* [JSON5](https://github.com/json5/json5) ⭐ 7,160 | 🐛 39 | 🌐 JavaScript | 📅 2024-10-25: JSON for humans. (Not an official successor to JSON.)
* [hjson](https://github.com/hjson/hjson) ⭐ 2,857 | 🐛 26 | 🌐 HTML | 📅 2026-04-20: 比 JSON5 更丰富，且相对更标准，有 [RFC 文档](https://hjson.github.io/rfc.html)。
* [jv](https://github.com/gistia/json-log-viewer) ⭐ 265 | 🐛 11 | 🌐 JavaScript | 📅 2022-12-07: JSON Log Viewer
* <https://www.json.cn/> : JSON 在线解析
* [JSON Patch](http://jsonpatch.com/): JSON 数据的 add、remove、replace、copy、move、test 操作
* [JSON Merge Patch](https://tools.ietf.org/html/rfc7386): RFC7386
* <https://www.json-generator.com/> : 根据语法随机生成 JSON 对象
* [extendsclass](https://extendsclass.com/json-generator.html): JSON data generator

### JSON Schema

* [json-schema-faker](https://github.com/json-schema-faker/json-schema-faker) ⭐ 3,448 | 🐛 1 | 🌐 JavaScript | 📅 2026-08-01: 根据 JSON Schema 生成数据
* <https://www.jsonschemavalidator.net/> : 在线校验 JSON Schema
* <https://spacetelescope.github.io/understanding-json-schema/index.html> : 目前最好的入门教程
* <https://jsonschema.net/> : 根据 JSON 生成 JSON Schema
* <https://www.schemastore.org/json/> : 各种现成的 JSON Schema 文件
  * <https://github.com/instrumenta/kubernetes-json-schema> ⭐ 338 | 🐛 21 | 📅 2023-07-22 : K8S JSON Schema 文件

### JSON Path

* [JsonPath](https://github.com/json-path/JsonPath) ⭐ 9,449 | 🐛 440 | 🌐 Java | 📅 2026-02-22
* <https://jsonpath.online/> : JSONPath Online Evaluator & Validator

## Lint

* [shellcheck](https://github.com/koalaman/shellcheck) ⭐ 39,969 | 🐛 1,138 | 🌐 Haskell | 📅 2026-08-04: linux shell script lint
* [commitlint](https://github.com/conventional-changelog/commitlint) ⭐ 18,717 | 🐛 82 | 🌐 TypeScript | 📅 2026-08-31: Lint git commit messages
* [hadolint](https://github.com/hadolint/hadolint) ⭐ 12,378 | 🐛 203 | 🌐 Haskell | 📅 2026-08-24: Dockerfile Lint <a name="commitlint"></a>
* [stylelint](https://github.com/stylelint/stylelint) ⭐ 11,516 | 🐛 138 | 🌐 JavaScript | 📅 2026-08-30
  * [csslint](https://github.com/CSSLint/csslint) ⭐ 4,811 | 🐛 227 | 🌐 JavaScript | 📅 2024-12-05: 备用
* [checkstyle](https://github.com/checkstyle/checkstyle) ⭐ 9,501 | 🐛 760 | 🌐 Java | 📅 2026-09-01: Java code lint
* [proselint](https://github.com/amperser/proselint) ⭐ 4,572 | 🐛 236 | 🌐 JavaScript | 📅 2026-08-26: 英文语法检查
  * [alex](https://github.com/get-alex/alex) ⭐ 5,099 | 🐛 28 | 🌐 JavaScript | 📅 2024-11-27: 英文语法检查
  * [write-good](https://github.com/btford/write-good) ⭐ 5,087 | 🐛 24 | 🌐 JavaScript | 📅 2025-03-10: 备选方案
* [ansible-lint](https://github.com/ansible/ansible-lint) ⭐ 3,904 | 🐛 114 | 🌐 Python | 📅 2026-08-31
* [yamllint](https://github.com/adrienverge/yamllint) ⭐ 3,452 | 🐛 167 | 🌐 Python | 📅 2026-08-19: YAML lint
* [HTMLHint](https://github.com/yaniswang/HTMLHint) ⭐ 3,306 | 🐛 43 | 🌐 JavaScript | 📅 2026-09-01: HTML lint
  * [tidy](https://github.com/htacg/tidy-html5) ⭐ 2,845 | 🐛 240 | 🌐 C | 📅 2024-05-04: 不明觉厉的 HTML lint。备用
* [markdownlint](https://github.com/mivok/markdownlint) ⭐ 2,076 | 🐛 110 | 🌐 Ruby | 📅 2026-09-01: markdown lint
* [jsonlint](https://github.com/zaach/jsonlint) ⭐ 1,992 | 🐛 80 | 🌐 JavaScript | 📅 2022-07-12: JSON lint
* [vint](https://github.com/Kuniwak/vint) ⭐ 707 | 🐛 90 | 🌐 Python | 📅 2023-12-29: vim script lint
* [editorconfig-checker](https://github.com/editorconfig-checker/editorconfig-checker) ⭐ 639 | 🐛 29 | 🌐 Go | 📅 2026-09-01: 兼容 .editorconfig，且可忽略文件。它提供额外的配置选项 .ecrc
* [editorconfig](http://editorconfig.org/): 最基础的代码风格规约
* [在线 JSON Lint](http://pro.jsonlint.com)

## Mock

* [jsoning](https://jsoning.com/api/): Mock API for testing and prototyping
* [insomnia](https://insomnia.rest): Mock, Test & Track HTTP Requests and Responses
  * <https://github.com/Kong/insomnia-mockbin> ⭐ 2,048 | 🐛 50 | 🌐 JavaScript | 📅 2026-08-31

## 网站

* [rrweb](https://github.com/rrweb-io/rrweb) ⭐ 20,098 | 🐛 423 | 🌐 TypeScript | 📅 2026-08-24: 网页浏览录制和回放
  * [Open Replay](https://github.com/openreplay/openreplay) ⭐ 12,622 | 🐛 180 | 🌐 TypeScript | 📅 2026-09-01
* [pageres](https://github.com/sindresorhus/pageres) ⭐ 9,734 | 🐛 0 | 🌐 TypeScript | 📅 2025-09-09: 网页截屏
* [sitemap.js](https://github.com/ekalinin/sitemap.js) ⭐ 1,712 | 🐛 31 | 🌐 TypeScript | 📅 2026-08-18: 生成 sitemap 的工具
* [temme](https://github.com/shinima/temme) ⭐ 271 | 🐛 3 | 🌐 TypeScript | 📅 2024-07-06: 利用 CSS 语法，从 HTML 提取出 JSON 数据
* <https://archive.ph/> : 永久保存网页内容。保存的页面来自用户提交的，不做自动抓取。生成短链接
  * <https://archive.org/> : 永久保存网页内容。保存的页面来自用户提交的和自动抓取的。生成链接很长
  * <https://perma.cc/> : 备用方案
* [Favicon 生成器](https://realfavicongenerator.net/)
  * [websiteplanet - favicon-generator](https://www.websiteplanet.com/zh-hans/webtools/favicon-generator/): 支持 gif

### 访问统计

* [umami](https://github.com/mikecao/umami) ⭐ 38,484 | 🐛 117 | 🌐 TypeScript | 📅 2026-09-01: website analytics alternative to Google Analytics.
* [rybbit](https://github.com/rybbit-io/rybbit) ⭐ 12,901 | 🐛 189 | 🌐 TypeScript | 📅 2026-08-31: 界面设计和功能都很优秀
* [不蒜子 busuanzi](https://busuanzi.ibruce.info/): 两行代码搞定站点访问统计

## SSL

* [mkcert](https://github.com/FiloSottile/mkcert) ⭐ 59,528 | 🐛 177 | 🌐 Go | 📅 2024-08-13: 零配置生成自签名证书。默认有效时间 825 天。
* [lego](https://github.com/go-acme/lego) ⭐ 9,844 | 🐛 107 | 🌐 Go | 📅 2026-09-01: 免费证书生成工具。简单好用，文档清晰。
  * [acme.sh](https://github.com/Neilpang/acme.sh) ⭐ 47,562 | 🐛 102 | 🌐 Shell | 📅 2026-08-31: 备选方案。支持 ZeroSSL.com、Letsencrypt.org、BuyPass.com、SSL.com、Pebble strict Mode，以及其他遵循 RFC8555 的 CA。支持模式 Webroot，Standalone，Standalone tls-alp，Apach，Nginx，DNS，DNS alias，Stateless。
  * [certbot](https://github.com/certbot/certbot) ⭐ 33,226 | 🐛 188 | 🌐 Python | 📅 2026-08-31: 备选方案。letsencrypt 官方证书生成工具
  * [dehydrated](https://github.com/lukas2511/dehydrated) ⭐ 6,245 | 🐛 83 | 🌐 Shell | 📅 2026-04-30: 备选方案
* [Fishdrowned/ssl](https://github.com/Fishdrowned/ssl) ⭐ 537 | 🐛 4 | 🌐 Shell | 📅 2024-07-26: 零配置生成自签名证书。比 mkcert 提供更丰富的配置选项。

## BSD

* [FreeBSD](https://www.freebsd.org/)
* [hackintosh](https://hackintosh.com/)

## [Linux](./linux/README.md)

## [命令行 CLI](./CLI/README.md)

## [Shell Script Development](./shell-script/README.md)

## 文件同步/备份/快照

* [syncthing](https://github.com/syncthing/syncthing) ⭐ 88,177 | 🐛 379 | 🌐 Go | 📅 2026-08-25: 文件自动同步
* [rclone](https://github.com/rclone/rclone) ⭐ 59,485 | 🐛 1,245 | 🌐 Go | 📅 2026-08-31: rsync for cloud storage. To sync files and directories to and from different cloud storage providers.
* [restic](https://github.com/restic/restic) ⭐ 35,810 | 🐛 583 | 🌐 Go | 📅 2026-09-01: 简单易用的备份工具。支持快照，加密。可与 rclone 搭配。不支持软链接，restore 会[报错](https://github.com/restic/restic/issues/2578) ⭐ 35,810 | 🐛 583 | 🌐 Go | 📅 2026-09-01。
  * [backrest](https://github.com/garethgeorge/backrest) ⭐ 7,238 | 🐛 354 | 🌐 TypeScript | 📅 2026-08-31: 集成 restic 和 rclone 的 WebUI。操作简单。
  * [rest-server](https://github.com/restic/rest-server) ⭐ 1,489 | 🐛 62 | 🌐 Go | 📅 2026-07-22: a high performance HTTP server that implements restic's REST backend API. 用于备份到远端。
* [borg](https://github.com/borgbackup/borg) ⭐ 13,672 | 🐛 221 | 🌐 Python | 📅 2026-09-01: 备选方案
* [timeshift](https://github.com/linuxmint/timeshift) ⭐ 4,257 | 🐛 233 | 🌐 Vala | 📅 2026-04-08: 备选方案。基于 rsync + hard link。支持快照、增量备份、BTRFS、自定义路径（默认屏蔽用户目录）。**不支持云存储**
* tar
  * 参考文章: <https://archive.ph/7R49W>
* rsync
* [duplicity](https://gitlab.com/duplicity/duplicity): 支持增量备份，软链接。不支持硬链接。
  * [duply](): duplicity 的前端程序
* [rescuezilla](https://rescuezilla.com/): 专门用来备份和恢复的 Linux 系统。基于 ubuntu。支持压缩。不支持加密。兼容 Clonezilla 导出的备份文件。支持各种虚拟硬盘(vdi、b)。图形化界面。有中文。全盘备份，不支持按文件备份。自带镜像文件浏览器
  * [Clonezilla](https://clonezilla.org/): 备选方案。备份和恢复系统。命令行交互菜单。全盘备份，不支持按文件备份，不支持快照。使用命令行备份貌似难度很高。还原到不同大小分区也可能出问题。
* [FreeFileSync](https://freefilesync.org/): 跨平台、开源。同步目录文件，可以 diff 文件列表。GUI 工具。
* 其他备份工具
  * [backintime](https://github.com/bit-team/backintime) ⭐ 2,660 | 🐛 144 | 🌐 Python | 📅 2026-08-31: 备选方案
  * <https://github.com/restic/others> ⭐ 756 | 🐛 13 | 📅 2023-11-05

## 数据恢复

* [testdisk](https://www.cgsecurity.org/wiki/TestDisk_CN)

## ISO 镜像制作与刻录

* mkisofs: 制作 ISO 镜像。Linux 命令
* 制作启动 U 盘
  * [Ventoy](https://github.com/ventoy/Ventoy) ⭐ 79,070 | 🐛 1,021 | 🌐 C | 📅 2026-08-06: 支持多个不同类型的镜像共存。只支持在 Windows/Linux/虚拟机 制作。
  * [rufus](https://github.com/pbatard/rufus) ⭐ 37,496 | 🐛 12 | 🌐 C | 📅 2026-08-24: 操作简单，可配置。只支持在 Windows 制作。
  * [etcher](https://github.com/balena-io/etcher) ⭐ 34,272 | 🐛 689 | 🌐 TypeScript | 📅 2026-06-02: 一键操作，不可配置。支持在 Windows/MacOS/Linux（不支持命令行）制作。
  * [bootiso](https://github.com/jsamr/bootiso) ⚠️ Archived: 只支持在 Linux 制作，且用于安装 Linux 系统。

## 数据库/存储

* [rustfs](https://github.com/rustfs/rustfs) ⭐ 31,595 | 🐛 41 | 🌐 Rust | 📅 2026-09-01: 对象存储，高性能，K8S-Native，兼容 S3

* [dolt](https://github.com/dolthub/dolt) ⭐ 24,318 | 🐛 706 | 🌐 Go | 📅 2026-09-01: 功能类似 Git 的数据库

* [turso](https://github.com/tursodatabase/turso) ⭐ 24,112 | 🐛 876 | 🌐 Rust | 📅 2026-09-01: an in-process SQL database, compatible with SQLite.

* [vitess](https://github.com/vitessio/vitess) ⭐ 21,283 | 🐛 1,088 | 🌐 Go | 📅 2026-09-01: MySQL Sharding Proxy。支持 k8s。Youtube 2011 年就开始跑了。

* [ceph](https://github.com/ceph/ceph) ⭐ 16,985 | 🐛 1,317 | 🌐 C++ | 📅 2026-09-01: 块存储，对象存储，文件存储

  ### postgres

* [pgcli](https://github.com/dbcli/pgcli) ⭐ 13,370 | 🐛 39 | 🌐 Python | 📅 2026-08-31: postgres 命令行客户端

* [mycli](https://github.com/dbcli/mycli) ⭐ 11,972 | 🐛 1 | 🌐 Python | 📅 2026-08-31: mysql 命令行客户端

* [pgweb](https://github.com/sosedoff/pgweb) ⭐ 9,488 | 🐛 55 | 🌐 Go | 📅 2026-07-26: postgres web 客户端

* [RedisInsight](https://github.com/RedisInsight/RedisInsight) ⭐ 8,800 | 🐛 76 | 🌐 TypeScript | 📅 2026-09-01: Redis GUI by Redis。支持 Docker 部署。

* [SQL 速查表](https://github.com/enochtangg/quick-SQL-cheatsheet/blob/master/README_zh-hans.md) ⭐ 5,455 | 🐛 11 | 📅 2020-10-01

* [pgbackrest](https://github.com/pgbackrest/pgbackrest) ⭐ 4,347 | 🐛 32 | 🌐 C | 📅 2026-08-24: 备份工具

* [pgbarman](https://github.com/EnterpriseDB/barman) ⭐ 3,224 | 🐛 39 | 🌐 Python | 📅 2026-08-27: 备份工具

* [UNQLite](https://github.com/symisc/unqlite) ⭐ 2,313 | 🐛 31 | 🌐 C | 📅 2026-05-01:

* [DataGrip](https://www.jetbrains.com/datagrip): 数据库 GUI  `Ⓜ`

* [SQL 工具](https://sqlable.com/)

* [SQLite](https://www.sqlite.org)

* [pgadmin](https://www.pgadmin.org/): postgres web 客户端

### Embeddable DB

* [LokiJS](https://github.com/techfort/LokiJS) ⭐ 6,826 | 🐛 35 | 🌐 JavaScript | 📅 2023-06-22: javascript embeddable / in-memory database
* [BuntDB](https://github.com/tidwall/buntdb) ⭐ 4,866 | 🐛 32 | 🌐 Go | 📅 2026-05-19: an embeddable, in-memory key/value database for Go with custom indexing and geospatial support

### 数据库设计

* <https://dbdiagram.io/> : 在线 ER 建模工具，通过 [dbml](https://github.com/holistics/dbml) ⭐ 3,682 | 🐛 94 | 🌐 JavaScript | 📅 2026-08-18 语法构建 ER 图。支持导出 SQL。
* [sqldbm](https://sqldbm.com/en/Home/): 目前做的最好（没有之一）的 ER 建模工具，目前免费。

### Database Versioning

* [migrate](https://github.com/golang-migrate/migrate) ⭐ 18,879 | 🐛 490 | 🌐 Go | 📅 2026-08-31: 用 Go 写的，支持 SQL，支持命令行和 Go 编程。
* [gh-ost](https://github.com/github/gh-ost) ⭐ 13,548 | 🐛 328 | 🌐 Go | 📅 2026-08-28: 与 flyway 不一样的实现方案，创建 shadow/ghost 表来作 schema migration。功能丰富。不基于 trigger，基于 bin-log。
* [flyway](https://github.com/flyway/flyway) ⭐ 10,050 | 🐛 256 | 🌐 Java | 📅 2026-08-26: 用 Java 写的，支持 SQL 和 Java 写 migration。没有 revert 概念。
* [sql-migrate](https://github.com/rubenv/sql-migrate) ⭐ 3,419 | 🐛 98 | 🌐 Go | 📅 2026-07-14: 用 Go 写的。备选

## [网络](./network/README.md)

## ProtoBuf

* [buf](https://github.com/bufbuild/buf) ⭐ 11,408 | 🐛 63 | 🌐 Go | 📅 2026-08-31: .proto 管理器
* [prototool](https://github.com/uber/prototool) ⚠️ Archived: .proto 管理器

## IM

* [Rocket.Chat](https://github.com/RocketChat/Rocket.Chat) ⭐ 46,059 | 🐛 4,011 | 🌐 TypeScript | 📅 2026-09-01: 开源版 Slack。built with Meteor，不支持推送
* Matrix Client
  * [Element](https://matrix.org/ecosystem/clients/element/): Matrix.org 官方出品，功能最全，UI 还不错。全平台支持。
  * [Cinny](https://app.cinny.in/): Web App，UI 简洁好看
  * ~~[FluffyChat](https://fluffychat.im/)~~: 不好用，功能简陋，不支持注册功能
  * <https://iamb.chat/> : 运行在终端的客户端
* Matrix Server
  * [dendrite](https://github.com/matrix-org/dendrite) ⚠️ Archived: Matrix homeserver written in Go
  * [synapse](https://github.com/element-hq/synapse) ⭐ 4,568 | 🐛 2,090 | 🌐 Python | 📅 2026-09-01: Synapse: Matrix homeserver written in Python/Twisted
  * [tuwunel](https://github.com/matrix-construct/tuwunel) ⭐ 2,484 | 🐛 71 | 🌐 Rust | 📅 2026-09-01: Official successor to [conduwuit](https://github.com/girlbossceo/conduwuit) ⚠️ Archived
    * [tuwunel-admin](https://github.com/knadh/tuwunel-admin) ⭐ 39 | 🐛 1 | 🌐 Rust | 📅 2026-06-28: tuwunel 的 admin 后台界面
  * [conduit](https://gitlab.com/famedly/conduit): Matrix homeserver written in Rust

## [Git](./git.md)

## [Chrome](./chrome/README.md)

## Bookmarklet

* <https://mcdlr.com/css-inject/>
* <https://mcdlr.com/js-inject/>
* <https://adrianroselli.com/2015/01/css-bookmarklets-for-testing-and-fixing.html>
* <https://css-tricks.com/web-development-bookmarklets/>

## 测试

### 字符串测试

附赠一个笑话，[一个 Bug 测试员走进一家酒吧](https://www.reddit.com/r/ProgrammerHumor/comments/31bgwm/a_bug_tester_walks_into_a_bar/)。

* [Big List of Naughty Strings](https://github.com/minimaxir/big-list-of-naughty-strings) ⭐ 47,706 | 🐛 108 | 🌐 Python | 📅 2024-04-18: 收集了一系列不正常的字符用来测试字符串校验

### [HTTP Benchmark](./network/README.md#http-benchmark)

### 基准测试 (Benchmark Test)

* [hyperfine](https://github.com/sharkdp/hyperfine) ⭐ 28,780 | 🐛 97 | 🌐 Rust | 📅 2026-04-30: 对某个命令进行 Benchmark
* [sysbench](https://github.com/akopytov/sysbench) ⭐ 6,784 | 🐛 217 | 🌐 C | 📅 2025-03-09: 对数据库和操作系统的 benchmark。支持 lua 脚本
* [bench-scripts](https://github.com/haydenjames/bench-scripts) ⭐ 1,190 | 🐛 1 | 📅 2024-07-01: 对 Linux 系统进行 Benchmark 的脚本
* [Programming Language and compiler](https://programming-language-benchmarks.vercel.app/): 对各种编程语言做 Benchmark。很全面。

### 压测 (Stress Test)

* [FIO](https://github.com/axboe/fio) ⭐ 6,351 | 🐛 237 | 🌐 C | 📅 2026-08-26: 测试硬盘 IO。开源。
* [stress-ng](https://github.com/ColinIanKing/stress-ng) ⭐ 2,751 | 🐛 2 | 🌐 C | 📅 2026-08-31: 对 CPU、内存、IO 的压力测试
  * [stress](https://fossies.org/linux/privat/old/stress-1.0.4.tar.gz/stress-1.0.4/doc/stress.html)
* [Geekbench](https://www.geekbench.com/): 对操作系统的压测工具。闭源。压测报告会自动上传到官网，多个压测报告可以进行比较。

## 密码相关

### 加密/解密

* [kbpgp](https://github.com/keybase/kbpgp) ⭐ 536 | 🐛 76 | 🌐 JavaScript | 📅 2026-08-27: Keybase 用 JS 实现的 PGP 程序
* [GPG](https://www.gnupg.org/)
* [keybase](https://keybase.io): 以社交系统为之背书的，开源的 PGP 工具、系统与托管服务器

### 密码管理

<a name="KeePass"></a>

* [KeeWeb](https://github.com/keeweb/keeweb) ⭐ 12,988 | 🐛 440 | 🌐 HTML | 📅 2026-05-08: 备选方案。[KeePass][] 的 GUI 客户端，跨平台
  * [keeweb-connect](https://chromewebstore.google.com/detail/keeweb-connect/pikpfmjfkekaeinceagbebpfkmkdlcjk): Chrome 插件，链接 KeeWeb 提供密码自动填充功能
  * [Keeweb Online](https://app.keeweb.info/): KeeWeb 网页版。备用方案
* [KeePass](http://keepass.info): 密码管理器
  * [keepass-diff](https://github.com/Narigo/keepass-diff) ⭐ 366 | 🐛 27 | 🌐 Rust | 📅 2024-08-17: A CLI-tool to diff Keepass (.kdbx) files. Useful, if syncing with Dropbox or NextCloud and getting multiple files due to conflicts.
  * 推荐将密码文件保存到（私有）网盘里，避免密码文件丢失。
* [KeePassXC](https://keepassxc.org/): [KeePass][] 的 GUI 客户端，跨平台。功能比 KeeWeb 强：可以随系统自启动，密码统计分析，密码健康检查等功能。
  * [KeePassXC-Browser](https://chrome.google.com/webstore/detail/keepassxc-browser/oboonakemofpalcgghocfoadofidjkkk): Chrome 插件，自动填充功能比 keeweb-connect 优秀
* [KeePassDX](https://www.keepassdx.com/): [KeePass][] 的 Android 客户端，UI 好看，功能丰富，支持 2FA
  * [Keepass2Android](https://play.google.com/store/apps/details?id=keepass2android.keepass2android\&hl=zh_CN): 备选方案，UI 比较复古，也挺好用的
  * [Keepass2Android 离线版](https://play.google.com/store/apps/details?id=keepass2android.keepass2android_nonet): 备选方案
* [strongbox](https://strongboxsafe.com/): iPhone 平台的 KeePass 密码管理器

## 编码

* <https://www.punycoder.com/> : Punycode
* [leet](https://www.wikiwand.com/en/Leet)
  * <https://1337.me/>
  * <https://www.gamehouse.com/blog/leet-speak-cheat-sheet/>

## 知识管理

* [iThoughtsX](https://www.toketaware.com): 思维导图 `Ⓜ`
  * [Thoughts-Search](https://github.com/adoyle-h/iThoughts-Search) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2021-10-20: iThoughtsX 命令行搜索工具 `⨀`

## 搜索引擎 Search Bar

* [ElasticSearch](https://github.com/elastic/elasticsearch) ⭐ 77,886 | 🐛 6,029 | 🌐 Java | 📅 2026-09-01: 企业级搜索引擎。Java 实现
* [MeiliSearch](https://github.com/meilisearch/meilisearch) ⭐ 59,158 | 🐛 322 | 🌐 Rust | 📅 2026-08-31: Rust 实现
* [typesense](https://github.com/typesense/typesense) ⭐ 26,496 | 🐛 874 | 🌐 C++ | 📅 2026-09-01: 类似 algolia。C++ 实现的。索引全存内存。
  * 可自己托管，也可以选择 [typesense cloud](https://cloud.typesense.org/) 服务，但它没有靠近中国的数据中心。
* [sonic](https://github.com/valeriansaliou/sonic) ⭐ 21,331 | 🐛 62 | 🌐 Rust | 📅 2026-08-26: Rust 实现。
* [flexsearch](https://github.com/nextapps-de/flexsearch) ⭐ 13,788 | 🐛 38 | 🌐 JavaScript | 📅 2026-06-28: 类似 lunr.js。虽然支持中文，但分词功能可能需要自己开发。
* [lunr.js](https://github.com/olivernn/lunr.js) ⭐ 9,201 | 🐛 130 | 🌐 JavaScript | 📅 2024-07-31: 轻量级的搜索方案。无须部署服务。支持多语言。现已无人维护。
  * [lunr-languages](https://github.com/MihaiValentin/lunr-languages) ⭐ 458 | 🐛 17 | 🌐 JavaScript | 📅 2026-08-09: 语言包。中文包的依赖加载有问题。
  * [全文索引](https://lunrjs.com/guides/index_prebuilding.html)存储在本地的一个 JSON 文件里，每次加载页面都会加载全文索引。如果网站内容很多，索引文件会很大。
* [Algolia](https://www.algolia.com/): 商业搜索引擎
  * [docsearch](https://github.com/algolia/docsearch) ⭐ 4,375 | 🐛 84 | 🌐 TypeScript | 📅 2026-08-28: 基于 algolia 服务的搜索框，搜索时需要请求 algolia api。
* [solr](https://solr.apache.org/): 基于 Lucene 的开源企业级搜索平台

### 停止词 Stop Words

停用词是指在信息检索中，为节省存储空间和提高搜索效率，在处理自然语言数据（或文本）之前或之后会自动过滤掉某些字或词，这些字或词即被称为 Stop Words（停用词）。
这些停用词都是人工输入、非自动化生成的，生成后的停用词会形成一个停用词表。但是，并没有一个明确的停用词表能够适用于所有的工具。

* 中文停止词
  * [goto456/stopwords](https://github.com/goto456/stopwords) ⭐ 5,540 | 🐛 6 | 📅 2024-01-25
* 英文停止词

## 邮件

* [react-email](https://github.com/resend/react-email) ⭐ 19,693 | 🐛 30 | 🌐 TypeScript | 📅 2026-08-31: 用 React 构建邮件
* [docker-mailserver](https://github.com/docker-mailserver/docker-mailserver) ⭐ 18,815 | 🐛 97 | 🌐 Shell | 📅 2026-08-31: 运行在容器内的邮件服务器，无需数据库。
* [nodemailer](https://github.com/nodemailer/nodemailer) ⭐ 17,666 | 🐛 2 | 🌐 JavaScript | 📅 2026-08-31: 邮件类库 (NodeJS)
* [Newton](https://cloudmagic.com/k/newton): 邮件客户端。也支持移动端 `Ⓜ`
* [mjml](https://mjml.io/): 邮件模板语言
* <https://www.mailgun.com/> : 发邮件的服务 `ⱳ`
  * <https://resend.com/> : 备选方案
* <http://mailchimp.com/> : 搭建邮件&发邮件的服务 `ⱳ`
* <https://ethereal.email/> : 伪 SMTP 服务，用于测试邮件发送
* <https://mail.tm/> : 临时邮件账号，注销很方便。记录临时账号的密码可以下次登录。

## 翻译

* [沉浸式翻译](https://github.com/immersive-translate/immersive-translate) ⭐ 18,691 | 🐛 402 | 📅 2026-08-31: 浏览器插件，开源免费，体验很好。
* [OpenCC](https://github.com/BYVoid/OpenCC) ⭐ 9,951 | 🐛 50 | 🌐 C++ | 📅 2026-08-26: 中文简体与繁体转换
* [translate-shell](https://github.com/soimort/translate-shell) ⭐ 7,506 | 🐛 117 | 🌐 Awk | 📅 2024-12-10: Command-line translator using Google Translate, Bing Translator, Yandex.Translate, etc.
* [Poedit](https://poedit.net): .po 翻译软件 `Ⓜ`。价格太贵，大版本升级坑。暂无替代方案
* <https://www.deepl.com/> : 基于 AI 的翻译器
* [Grammarly](https://www.grammarly.com/): 提供英文语法纠错的 Web 服务。有 Chrome 插件，体验不错。

## [Windows App](./Windows/README.md)

## [Mac App](./Mac/README.md)

## [字体](./design/README.md#字体)

## [Design](./design/README.md)

## Emoji

* <https://emojifinder.com/> : 根据输入搜索相关的 emoji
* <https://emojipedia.org/> : emoji 百科
* <http://www.emoji-cheat-sheet.com>
  * [源码](https://github.com/WebpageFX/emoji-cheat-sheet.com/) ⭐ 6,322 | 🐛 56 | 🌐 HTML | 📅 2022-05-28
* <http://unicode.org/emoji/charts-beta/full-emoji-list.html> : 完整的 emoji 列表

## Unicode

* <https://symbl.cc/cn/>
* <https://www.compart.com/en/unicode> : 找 unicode 字符

## 命名

* [codelf](http://unbug.github.io/codelf/): 解决命名烦恼
* <https://namelix.com/> : 解决项目命名困难
* <https://namae.dev/> : 检查名称是否已存在
  * [源码](https://github.com/uetchy/namae) ⭐ 715 | 🐛 15 | 🌐 TypeScript | 📅 2023-05-02

## 团队协作

* [airtable](https://www.airtable.com/): 商业方案，小团队免费
  * [nocodb](https://github.com/nocodb/nocodb) ⭐ 64,794 | 🐛 711 | 🌐 TypeScript | 📅 2026-09-01: 备选方案。开源的

### 即时通讯

* [mattermost](https://github.com/mattermost/mattermost-server) ⭐ 38,954 | 🐛 1,007 | 🌐 TypeScript | 📅 2026-09-01: slack 的开源替代品。即时聊天。

## ChatOps

* [wechaty](https://github.com/wechaty/wechaty) ⭐ 22,994 | 🐛 199 | 🌐 TypeScript | 📅 2025-12-21: 聊天机器人开发框架

## 电子书

交流学习使用，请勿用于非法用途。

* <https://zh.singlelogin.re/> : zlibrary 官方网站
* <https://zh.annas-archive.org/> : 安娜的档案，下载链接分付费和免费，付费会员下载速度快，免费的下载要排队几分钟，但下载速度也不慢。
* <https://bookpan.net/>
* <https://ylibrary.org/>
* <https://search.zhelper.net/> : 搜索前端，调用其他电子书平台的 API。直接打开链接是不可用的。需查阅[使用帮助](https://docs.zhelper.net/search/)。
  * <https://zlib.knat.network/> : 类似 zhelper 的搜索前端
* <https://bookfere.com/tools> （[永久链接](https://archive.md/pKKqS)）

### 电子书阅读器

* [legado](https://github.com/gedoor/legado) ⭐ 47,047 | 🐛 18 | 🌐 Kotlin | 📅 2026-05-27: 安卓平台的电子书阅读器
* [koreader](https://github.com/koreader/koreader) ⭐ 29,411 | 🐛 1,324 | 🌐 Lua | 📅 2026-09-01: 转为水墨屏设计的电子书阅读器
* [koodo-reader](https://github.com/troyeguo/koodo-reader) ⭐ 28,024 | 🐛 272 | 🌐 JavaScript | 📅 2026-09-01: 跨平台的电子书阅读器。不支持移动端
* [calibre](https://github.com/kovidgoyal/calibre/) ⭐ 25,788 | 🐛 6 | 🌐 Python | 📅 2026-09-01: 开源电子书管理器，支持格式转换。
  * [calibre-web](https://github.com/janeczku/calibre-web) ⭐ 18,080 | 🐛 397 | 🌐 Fluent | 📅 2026-08-29
  * [DeDRM\_tools](https://github.com/noDRM/DeDRM_tools/) ⭐ 10,283 | 🐛 452 | 🌐 Python | 📅 2024-11-10: calibre 插件。去除电子书的 DRM

## 服务 (Service)

* [Mastodon](https://github.com/mastodon/mastodon) ⭐ 50,258 | 🐛 4,516 | 🌐 Ruby | 📅 2026-09-01: 微博客社区
* [ntfy](https://github.com/binwiederhier/ntfy) ⭐ 33,921 | 🐛 375 | 🌐 Go | 📅 2026-08-27: Send push notifications to your phone or desktop using PUT/POST
* [ossinsight](https://github.com/pingcap/ossinsight) ⭐ 2,503 | 🐛 23 | 🌐 TypeScript | 📅 2026-09-01: <https://ossinsight.io/> Analysis, Comparison, Trends, Rankings of Github Repos and events
* [whoami](https://github.com/traefik/whoami) ⭐ 1,416 | 🐛 22 | 🌐 Go | 📅 2026-07-29: 返回请求者的 http request 信息。
* [docker-nfs-server](https://github.com/ehough/docker-nfs-server) ⭐ 799 | 🐛 49 | 🌐 Shell | 📅 2023-06-04: A lightweight, robust, flexible, and containerized NFS server.
* <https://www.clahub.com/> : CLA 签署服务，开源托管。[源码](https://github.com/clahub/clahub) ⭐ 259 | 🐛 28 | 🌐 TypeScript | 📅 2026-06-28
* [PlantUML Gist](https://github.com/linux-china/plantuml-gist) ⭐ 97 | 🐛 5 | 🌐 Java | 📅 2019-03-07: 基于托管在 Gist 的 [PlantUML][] 在线生成 UML 图
* [在线 sed 编辑器](http://sed.js.org)
* [Wikiwand](http://www.wikiwand.com/): Wikipedia Modernized。非常漂亮的 Wikipedia 阅读器
* <https://www.vectorizer.io/> : 位图转成矢量图 (SVG)
* <https://www.uuidgenerator.net/> : uuid 生成器
* <https://alternativeto.net/> : 搜索软件或服务其他替代方案
* <https://sesme.co/> : 阅后即焚

### 在线工具箱 (Online Toolbox)

* <https://ipcheck.ing/> :  IP 工具箱。轻松检查你的 IP，IP 地理位置，检查 DNS 泄漏，检查 WebRTC 连接，速度测试，ping 测试，MTR 测试，检查网站可用性，查询 Whois 信息等等。可自部署，源码见 [MyIP](https://github.com/jason5ng32/MyIP) ⭐ 11,786 | 🐛 24 | 🌐 JavaScript | 📅 2026-08-31。
* [CyberChef](https://gchq.github.io/CyberChef/): 开源的，在线提供编码/解码，压缩，数据分析，时间戳，代码格式化等功能。
* <https://it-tools.tech/> : 开源的，可以用 Docker 自部署。
  * <https://github.com/sharevb/it-tools> ⭐ 1,587 | 🐛 91 | 🌐 Vue | 📅 2026-08-30 : 原仓库维护太慢，这个 Fork 比较好
* <https://extendsclass.com/> : 有语法校验器，加/解密，格式转换，Diff 工具，各种生成器，前端压缩等工具。
* <https://cloudconvert.com/> : 在线服务，万能的格式转换器
  * <https://convertio.co/> : 备用服务

### 自部署的服务 (Self-Host Service)

* <https://github.com/awesome-selfhosted/awesome-selfhosted> ⭐ 316,443 | 🐛 0 | 📅 2026-09-01
* [rustdesk](https://github.com/rustdesk/rustdesk) ⭐ 122,304 | 🐛 139 | 🌐 Rust | 📅 2026-09-01: 开源的远程控制软件 (VNC)。支持手机控制电脑，电脑控制手机。支持全平台、多语言。国产软件。
  * [rustdesk-server](https://github.com/rustdesk/rustdesk-server) ⭐ 10,355 | 🐛 176 | 🌐 Rust | 📅 2026-08-07: 自建中继服务器
* [webhook](https://github.com/adnanh/webhook) ⭐ 12,103 | 🐛 127 | 🌐 Go | 📅 2026-08-05: a lightweight incoming webhook server to run shell commands
* [enclosed](https://github.com/CorentinTh/enclosed) ⭐ 2,067 | 🐛 73 | 🌐 TypeScript | 📅 2026-08-26: 阅后即焚服务

### 定时任务

* [xyops](https://github.com/pixlcore/xyops) ⭐ 6,119 | 🐛 38 | 🌐 JavaScript | 📅 2026-08-30: [Cronicle](https://github.com/jhuckaby/Cronicle) ⭐ 5,813 | 🐛 333 | 🌐 JavaScript | 📅 2026-08-29 的继任者。定时任务 + Workflow。Server + Agent 部署架构。部署简单。支持 Docker。功能丰富，界面友好。BSD-3 开源协议。

### WAF

* [SafeLine](https://github.com/chaitin/SafeLine) ⭐ 22,474 | 🐛 65 | 🌐 Go | 📅 2026-08-26: 中国公司做的雷池系统。UI 做的不错。
* [bunkerweb](https://github.com/bunkerity/bunkerweb) ⭐ 10,888 | 🐛 161 | 🌐 Python | 📅 2026-09-01: 「待评价」
* [ModSecurity](https://github.com/owasp-modsecurity/ModSecurity) ⭐ 9,759 | 🐛 344 | 🌐 C++ | 📅 2026-07-28: cross platform web application firewall (WAF) engine for Apache, IIS and Nginx. It has a robust event-based programming language which provides protection from a range of attacks against web applications and allows for HTTP traffic monitoring, logging and real-time analysis.
  * [OWASP CRS](https://github.com/coreruleset/coreruleset) ⭐ 3,253 | 🐛 101 | 🌐 Python | 📅 2026-09-01: ModSecurity 的防火墙规则集
  * [modsecurity-crs-docker](https://github.com/coreruleset/modsecurity-crs-docker) ⭐ 448 | 🐛 13 | 🌐 Dockerfile | 📅 2026-08-26: Official ModSecurity Docker + Core Rule Set (CRS) images

### 短链接

* [Dub](https://github.com/steven-tey/dub) ⭐ 24,643 | 🐛 147 | 🌐 TypeScript | 📅 2026-09-01: 开源的短链接服务，自带访问统计。部署复杂，不支持 docker 部署。
* [YOURLS](https://github.com/YOURLS/YOURLS) ⭐ 12,181 | 🐛 48 | 🌐 PHP | 📅 2026-08-31: 备选方案
* [sink](https://github.com/ccbikai/sink) ⭐ 7,070 | 🐛 16 | 🌐 Vue | 📅 2026-08-20: 基于 Cloudflare Page 部署的短链接服务，有访问统计功能。部署简单。
* [shlink](https://github.com/shlinkio/shlink) ⭐ 5,254 | 🐛 22 | 🌐 PHP | 📅 2026-08-06: 短链服务。功能挺全。

### 评论系统

* [remark42](https://github.com/umputun/remark42) ⭐ 5,599 | 🐛 107 | 🌐 Go | 📅 2026-08-31: 评论系统
  * [waline](https://github.com/walinejs/waline) ⭐ 3,110 | 🐛 86 | 🌐 JavaScript | 📅 2026-09-01: 备选方案
  * [Artalk](https://github.com/ArtalkJS/Artalk) ⭐ 2,328 | 🐛 104 | 🌐 Go | 📅 2026-08-12: 备选方案
* [cusdis](https://github.com/djyde/cusdis) ⚠️ Archived: Disqus 替代品
* [Disqus](https://disqus.com/): 国外的免费商业评论系统，用户体验好。但国内被墙
  * [DisqusJS](https://github.com/SukkaW/DisqusJS) ⭐ 666 | 🐛 10 | 🌐 TypeScript | 📅 2026-08-27: 让 Disqus 可以在国内访问，但是只读，不能发表评论

### 图床

* [PicGo](https://github.com/Molunerfinn/PicGo) ⭐ 27,110 | 🐛 27 | 🌐 TypeScript | 📅 2026-08-23: 图床管理软件，支持各种图床服务，包括 Github。Mac 安装失败见 FAQ。
  * [picgo-plugin-s3](https://github.com/wayjam/picgo-plugin-s3) ⭐ 235 | 🐛 10 | 🌐 TypeScript | 📅 2026-02-15
  * [picgo-plugin-freeimagehost-uploader](https://github.com/quul/picgo-plugin-freeimagehost-uploader) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2023-12-10
* <https://sm.ms/> : 免费公益的图床，中国不可访问
  * <https://smms.app/> : 中国可访问的免费图床
* <https://freeimage.host/> : 免费图床，单张图片最大 64 MB，注册后 128MB，自动生成缩略图
* <https://imgur.com/> : 国外的图床
* <https://cloudinary.com/>

## 网盘

* [Nextcloud](https://github.com/nextcloud/server) ⭐ 36,657 | 🐛 3,627 | 🌐 PHP | 📅 2026-09-01: 开源的网盘方案，客户端支持很多平台。用户体验很好，可与商业产品竞争。支持插件。
  * [linuxserver/nextcloud](https://hub.docker.com/r/linuxserver/nextcloud): nextcloud 官方的 AIO 镜像太烂，推荐用 linuxserver 的
  * Android 的 Nextcloud 客户端不要从 Google Play 下载，因为它会限制从 Nextcloud 下载 APK 文件。推荐从 F-Droid 下载。
* [Seafile](https://github.com/haiwen/seafile) ⭐ 15,188 | 🐛 92 | 🌐 C | 📅 2026-08-28
* [cryptomator](https://cryptomator.org/): 开源软件。将文件加密存储在任意网盘上。兼容全平台，电脑端免费，移动端收费。安卓推荐通过F-Droid 安装，然后到官网买授权。Google Play 的价格是官网授权价的两倍。
* [123 云盘](https://www.123pan.com/): 上传和下载速度都能跑满。2T 免费空间。客户端不能挂载到本地目录，客户端很差。使用 WebDav 需要购买会员。WebDav 功能问题很多。
* [阿里云盘](https://www.aliyundrive.com/): 使用 WebDav 需要额外付费。
* [Mega](https://mega.nz/): 免费版 25G 空间。需要翻墙
* [Dropbox](https://dropbox.com/): 免费版 3.8G 空间。需要翻墙
  * [Maestral](https://maestral.app/): 开源的 Dropbox 客户端。有 CLI 工具，支持 Linux。
* [Trainbit](https://trainbit.com/)
* [百度网盘秒传链接转存](https://rapidupload.1kbtool.com/)
* [钛盘](https://ttttt.link)
  * [国际版](https://tmp.link)

## 临时共享

* [localsend](https://github.com/localsend/localsend) ⭐ 89,849 | 🐛 1,096 | 🌐 Dart | 📅 2026-08-31: 类似 PairDrop。只不过是安装 app，不是网页形式。全平台支持。
* [transfer.sh](https://github.com/dutchcoders/transfer.sh) ⭐ 15,891 | 🐛 62 | 🌐 Go | 📅 2026-06-13: 共享文件的命令行程序
* [PairDrop](https://github.com/schlagmichdoch/PairDrop) ⭐ 11,298 | 🐛 110 | 🌐 JavaScript | 📅 2026-04-22: 通过网页在局域网内端到端传输文件和消息。可用 Docker 自己部署。
* [OnionShare](https://github.com/onionshare/onionshare) ⭐ 7,066 | 🐛 80 | 🌐 Python | 📅 2026-08-18: 开源工具，可让您使用 Tor 网络安全、匿名地共享文件、托管网站并与朋友聊天。
  * [onionshare-android](https://github.com/onionshare/onionshare-android) ⭐ 286 | 🐛 18 | 🌐 Kotlin | 📅 2025-12-12
* [奶牛快传](https://cowtransfer.com/) : 临时文件分享，很好用。国内服务
* <https://wormhole.app/> : 端到端加密，自动过期，单个文件最大 10 GB

## 爬虫/Archive

* [ArchiveBox](https://github.com/ArchiveBox/ArchiveBox) ⭐ 28,215 | 🐛 161 | 🌐 Python | 📅 2026-09-01: 自己搭建 Archive 网站。
* [colly](https://github.com/gocolly/colly) ⭐ 25,493 | 🐛 193 | 🌐 Go | 📅 2026-08-14: Go 语言编写的爬虫框架
* [katana](https://github.com/projectdiscovery/katana) ⭐ 17,366 | 🐛 25 | 🌐 Go | 📅 2026-08-31: 「待评价」
* [httrack](https://www.httrack.com/): 命令行或者图形化的爬虫工具，参数很丰富
* `wget -r`: 简易版，有诸多限制

### 爬虫代理池

* [proxy\_pool](https://github.com/jhao104/proxy_pool) ⭐ 23,654 | 🐛 298 | 🌐 Python | 📅 2026-06-15
* <https://proxy.mimvp.com/>

## 静态文件服务

* [caddy](https://github.com/caddyserver/caddy) ⭐ 75,379 | 🐛 276 | 🌐 Go | 📅 2026-08-31: Fast and extensible multi-platform HTTP/1-2-3 web server with automatic HTTPS。[Docker Alpine 镜像](https://hub.docker.com/_/caddy)大小 16 MB。
* [http-server](https://github.com/http-party/http-server) ⭐ 14,231 | 🐛 108 | 🌐 JavaScript | 📅 2026-04-15: NodeJS 写的。
* [static-web-server](https://github.com/static-web-server/static-web-server) ⭐ 2,342 | 🐛 36 | 🌐 Rust | 📅 2026-08-20: 轻量级文件服务器。[Docker Alpine 镜像](https://hub.docker.com/r/joseluisq/static-web-server)大小 3 MB。
* [lipanski/docker-static-website](https://github.com/lipanski/docker-static-website) ⭐ 1,001 | 🐛 1 | 🌐 Dockerfile | 📅 2025-08-05: 基于 busybox 自带的 httpd 程序。Docker 镜像大小 154KB。功能有限。

## 文件管理服务

* [OpenList](https://github.com/OpenListTeam/OpenList) ⭐ 24,432 | 🐛 259 | 🌐 Go | 📅 2026-09-01: 支持多种云盘存储的文件管理程序。支持在线浏览图片、视音频。支持流式传输。缺点是大文件传输时会报错。
  * [xlist](https://github.com/xlist-io/xlist) ⭐ 598 | 🐛 44 | 🌐 Dart | 📅 2024-06-01: OpenList 的 iOS 和 Android 客户端。
* [dufs](https://github.com/sigoden/dufs) ⭐ 10,685 | 🐛 13 | 🌐 Rust | 📅 2026-06-29: 轻量级文件服务器。支持 webdav。可拖拽文件实现上传。基本的多用户权限控制。支持 API 请求操作。
* [FileBrowser Quantum](https://github.com/gtsteffaniak/filebrowser) ⭐ 7,971 | 🐛 176 | 🌐 Go | 📅 2026-08-31: FileBrowser Quantum provides an easy way to access and manage your files from the web. FileBrowser Quantum  is a Fork from FileBrowser.

## 静态文件托管

* <http://surge.sh>  Static web publishing for Front-End Developers. 设计非常优雅，强烈推荐！
* <https://www.netlify.com/>

## CMS

* [strapi](https://github.com/strapi/strapi) ⭐ 73,050 | 🐛 551 | 🌐 TypeScript | 📅 2026-09-01
* [Ghost](https://github.com/TryGhost/Ghost) ⭐ 55,095 | 🐛 139 | 🌐 JavaScript | 📅 2026-09-01
* [netlify-cms](https://github.com/netlify/netlify-cms) ⭐ 19,331 | 🐛 592 | 🌐 JavaScript | 📅 2026-08-31: 基于 Git 服务（比如 github、gitlab）的 Open API 的 CMS。开源项目挺有用。商业项目不适合用。
* [keystone](https://github.com/keystonejs/keystone) ⭐ 9,966 | 🐛 137 | 🌐 TypeScript | 📅 2026-09-01: Headless CMS. Built with GraphQL and React
* [ROAPI](https://github.com/roapi/roapi) ⭐ 3,428 | 🐛 66 | 🌐 Rust | 📅 2026-03-25: 把数据源直接以 GraphQL、SQL、RESTful API 暴露。
* [headless cms](https://github.com/netlify/headlesscms.org) ⚠️ Archived

## PaaS

[PAAS comparison - Dokku vs Flynn vs Deis vs Kubernetes vs Docker Swarm (2017)](http://www.jancarloviray.com/blog/paas-comparison-2017-dokku-flynn-deis-kubernetes-docker-swarm/)

* [kubernetes](https://kubernetes.io/)
* 开源自部署的 Heroku/Netlify/Verce 替代品
  * [dokploy](https://github.com/Dokploy/dokploy) ⭐ 37,011 | 🐛 663 | 🌐 TypeScript | 📅 2026-09-01
  * [coolify](https://github.com/coollabsio/coolify) ⭐ 61,270 | 🐛 668 | 🌐 PHP | 📅 2026-09-01
  * [caprover](https://github.com/caprover/caprover) ⭐ 15,151 | 🐛 176 | 🌐 TypeScript | 📅 2026-08-31
  * [dokku](https://github.com/dokku/dokku) ⭐ 32,123 | 🐛 38 | 🌐 Shell | 📅 2026-08-31
* [planetscale](https://planetscale.com/): Serverless MySQL 服务，5GB 免费使用量。
* [railway.app](https://railway.app/): 非常棒的应用托管平台。每月赠送 $5，500 小时的免费用量。缺点是部署后就不能停止服务，只能删了部署重来。
* <https://vercel.com/>
* <https://claw.cloud/> : 支持 docker 部署，每个月 $5 免费用量。支持多个 region，中国访问速度良好
* <https://fly.io/> 免费版支持 3 shared-cpu-1x 256mb VMs, 3GB 存储，160GB 输出带宽。
* <https://deta.space/> 免费服务
* <https://www.koyeb.com/>
* <https://qoddi.com/>
* <https://adaptable.io/>
* <https://render.com/>

## 虚拟主机 (Web Hosting Account)

虚拟主机就是多个客户共用一台服务器，共享服务器资源。虚拟主机用户无法用 root 权限，无法 sudo，无法运行容器。

* <https://www.serv00.com/> : 3GB SSD, 512MB RAM, 3 个端口, 无带宽限制, FreeBSD 系统，16 个数据库。提供 ssh server、email server、ftp。无广告，可免费用十年。不能运行容器
  * **必须每 3 个月登录一次控制面板或 SSH，否则会被注销账号。**
  * 默认后台 Web 界面是波兰语，点右上角的 Zmień język 可修改成英语。
  * 默认情况，需要访问 <https://panel8.serv00.com/permissions/binexec> 按下 enable 按钮。或者执行 `devil binexec on` 也行。然后重新登录 ssh 即可。
  * 启动占用端口的服务，需要到 <https://panel8.serv00.com/port/> 预约端口，因为同一台机器上有多个用户使用，别人的进程可能占用了端口。

## Serverless

* [serverless/serverless](https://github.com/serverless/serverless) ⭐ 46,920 | 🐛 1,216 | 🌐 JavaScript | 📅 2026-08-31
* [apex/up](https://github.com/apex/up) ⭐ 8,792 | 🐛 293 | 🌐 Go | 📅 2024-03-15: 值得期待
  * <https://hackernoon.com/up-b3db1ca930ee>
* [kubeless](https://github.com/kubeless/kubeless) ⚠️ Archived: FaaS in k8s

### Cloudflare

* [sefinek/Cloudflare-WAF-Expressions](https://github.com/sefinek/Cloudflare-WAF-Expressions) ⭐ 214 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-28: Cloudflare WAF 规则
  * [SocolSRT/cloudflare-rules](https://github.com/SocolSRT/cloudflare-rules) ⭐ 234 | 🐛 1 | 📅 2026-03-15: 同上
* <https://workers.cloudflare.com/> : cloudflare 提供的边缘计算服务

## microVM

* [firecracker](https://github.com/firecracker-microvm/firecracker) ⭐ 36,412 | 🐛 109 | 🌐 Rust | 📅 2026-09-01: Secure and fast microVMs for serverless computing。AWS 出品
* [kubevirt](https://github.com/kubevirt/kubevirt) ⭐ 7,036 | 🐛 575 | 🌐 Go | 📅 2026-09-01: 「待评价」KubeVirt is a virtual machine management add-on for Kubernetes. The aim is to provide a common ground for virtualization solutions on top of Kubernetes.
  * <https://katacontainers.io/> : 备选方案
* [weaveworks/ignite](https://github.com/weaveworks/ignite/) ⚠️ Archived: a declarative Firecracker microVM administration tool

## 跳板机/堡垒机

* [jumpserver](https://github.com/jumpserver/jumpserver) ⭐ 31,483 | 🐛 88 | 🌐 Python | 📅 2026-09-01
* [teleport](https://github.com/gravitational/teleport) ⭐ 20,871 | 🐛 3,330 | 🌐 Go | 📅 2026-09-01

## REPL

* [repl.it](https://repl.it/languages): 运行在浏览器的 REPL
* [runkit](https://runkit.com/home): 非常酷！在前端直接引用 npm 包编写代码 `ⱳ`
* <https://codesandbox.io>

## 正则表达式 (Regex)

* [Learn regex the easy way](https://github.com/ziishaned/learn-regex) ⭐ 46,093 | 🐛 65 | 📅 2025-08-25
* [grex](https://github.com/pemistahl/grex) ⭐ 8,178 | 🐛 18 | 🌐 Rust | 📅 2026-02-27: 根据给出的文本，自动给出合适的正则表达式
* 正则表达式编辑器
  * <https://regexr.com/> : 仅支持 JS/PHP/Perl
  * <https://regex101.com/> : 仅支持 JS/PHP/Perl/Python/Go/Java/C#/Rust
* 正则表达式可视化
  * <https://regexper.com>
  * <https://pythonium.net/regex> : 可视化和校验。仅支持 Python

## 语法分析/AST

* [tree-sitter](https://github.com/tree-sitter/tree-sitter) ⭐ 26,813 | 🐛 97 | 🌐 Rust | 📅 2026-09-01: A parser generator tool and an incremental parsing library. It can build a concrete syntax tree for a source file and efficiently update the syntax tree as the source file is edited.
* [ast-grep](https://github.com/ast-grep/ast-grep) ⭐ 15,716 | 🐛 42 | 🌐 Rust | 📅 2026-08-31: A CLI tool for code structural search, lint and rewriting.
  * [GritQL](https://github.com/honeycombio/gritql) ⭐ 4,586 | 🐛 142 | 🌐 Rust | 📅 2026-08-30: 备选方案

## 数据可视化

* [kibana](https://github.com/elastic/kibana) ⭐ 21,277 | 🐛 14,296 | 🌐 TypeScript | 📅 2026-09-01
* [Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) ⭐ 20,953 | 🐛 29 | 🌐 JavaScript | 📅 2025-12-27: 中国省、地、县、乡、村级数据。
* [Grafana](https://grafana.com/grafana)

### 地图

* [derive](https://github.com/erik/derive) ⭐ 587 | 🐛 9 | 🌐 JavaScript | 📅 2026-08-27: 足迹热力图
* [Mapbox GL JS](https://docs.mapbox.com/mapbox-gl-js/guides/): 地图可视化

## 日志

* [goaccess](https://github.com/allinurl/goaccess) ⭐ 20,889 | 🐛 449 | 🌐 C | 📅 2026-08-31: Web 日志分析终端工具
* [toolong](https://github.com/Textualize/toolong) ⭐ 3,942 | 🐛 37 | 🌐 Python | 📅 2024-08-05: 针对大文件日志的终端阅读器
* [hl](https://github.com/pamburus/hl) ⭐ 3,275 | 🐛 13 | 🌐 Rust | 📅 2026-08-31: JSON 日志阅读器
* [gonzo](https://github.com/control-theory/gonzo) ⭐ 2,759 | 🐛 18 | 🌐 Go | 📅 2026-07-15: 日志分析终端工具。加载大文件非常慢。

## 交互式 Notebook

* [JupyterLab](https://github.com/jupyterlab/jupyterlab) ⭐ 15,281 | 🐛 2,603 | 🌐 TypeScript | 📅 2026-09-01: Jupyter 新的 Web 界面。
  * [介绍](https://zhuanlan.zhihu.com/p/33898478)
  * [DEMO](https://mybinder.org/v2/gh/jupyterlab/jupyterlab-demo/master?urlpath=lab/tree/demo)
* [nteract](https://github.com/nteract/nteract) ⭐ 165 | 🐛 32 | 🌐 Rust | 📅 2026-09-01: 基于 Jupyter 的前端跨平台项目
* [Jupyter](http://jupyter.org/): 交互式可编程的 notebook，主要支持 python。也可扩展支持其他语言
* 吃灰但值得一看的项目
  * [EVE](https://github.com/witheve/eve) ⭐ 7,223 | 🐛 71 | 🌐 TypeScript | 📅 2018-03-20: 「[团队解散](https://github.com/witheve/Eve/issues/889#issuecomment-395056593) ⭐ 7,223 | 🐛 71 | 🌐 TypeScript | 📅 2018-03-20」非常酷的概念，Literate Programming 的一种实现，Medium 式编程。
  * [kajero](https://github.com/joelotter/kajero) ⭐ 1,855 | 🐛 12 | 🌐 JavaScript | 📅 2017-06-27: 「无人维护」Interactive JavaScript notebooks with clever graphing
* <https://mybinder.org/>
  * 源码 [binderhub](https://github.com/jupyterhub/binderhub) ⭐ 2,669 | 🐛 272 | 🌐 Python | 📅 2026-09-01
* [Quarto](https://quarto.org/): an open-source scientific and technical publishing system built on Pandoc

## 简历

* [online-cv](https://github.com/sharu725/online-cv) ⭐ 3,491 | 🐛 32 | 🌐 JavaScript | 📅 2025-08-12: 适用于生成简历文档
* [resumed](https://github.com/rbardini/resumed) ⭐ 549 | 🐛 3 | 🌐 TypeScript | 📅 2025-09-19: 基于 jsonresume 生成静态网页
  * <https://jsonresume.org/> : 用 JSON 描述简历
  * <https://jsonresume.org/themes/> : 别人基于 jsonresume 做的主题

## [Zig](./zig.md)

## [Lua](./lua.md)

## [Python](./python.md)

## [Java](./java/README.md)

## [Golang](./go/README.md)

## [NodeJS](./nodejs/README.md)

## [TypeScript](./typescript/README.md)

## [WebAssembly](./wasm.md)

## [Nix](./nix/README.md)

## [前端开发](./FE/README.md)

## [Docker](./docker/README.md)

## [K8S/Kubernetes](./k8s.md)

## [硬件](./hardware.md)

## [HASS (Home Assistant)](./hass/README.md)

## 虚拟化

* [Vagrant](https://github.com/hashicorp/vagrant) ⭐ 27,204 | 🐛 753 | 🌐 Ruby | 📅 2026-08-31: 家用、商用方案
  * [bento](https://github.com/chef/bento) ⭐ 4,447 | 🐛 21 | 🌐 HCL | 📅 2026-08-08: build minimal Vagrant baseboxes
  * [vagrant-vbguest](https://github.com/dotless-de/vagrant-vbguest) ⚠️ Archived: 安装 VirtualBox Guest Additions 以支持宿主机与虚拟机共享目录的双向同步
  * [vagrant-scp](https://github.com/invernizzi/vagrant-scp) ⭐ 313 | 🐛 14 | 🌐 Ruby | 📅 2022-03-03: Vagrant 支持 scp
  * <https://app.vagrantup.com/> : vagrant box 仓库
  * [Vagrant Manager](http://vagrantmanager.com/): Vagrant 管理器。菜单栏工具。
* [flint](https://github.com/volantvm/flint) ⭐ 1,699 | 🐛 13 | 🌐 TypeScript | 📅 2026-04-28: A single binary with a modern Web UI, CLI, and API for KVM, for developers, sysadmins, and home labs who want zero bloat and maximum efficiency.
* [Proxmox VE](https://proxmox.com/en/proxmox-ve): 开源方案，基于 Debian 开发的 Linux 系统。支持 KVM 和 LXC。
* [VirtualBox](https://www.virtualbox.org/): 家用、商用方案

### libvirt/KVM

* [kimchi](https://github.com/kimchi-project/kimchi) ⭐ 3,200 | 🐛 335 | 🌐 JavaScript | 📅 2023-01-04: Kimchi manages KVM guests through libvirt. The management interface is accessed over the web using a browser that supports HTML5.
* [WebVirtCloud](https://github.com/retspen/webvirtcloud) ⭐ 1,875 | 🐛 203 | 🌐 JavaScript | 📅 2026-04-20: virtualization web interface for admins and users
* [KVM](https://www.linux-kvm.org/page/Main_Page): 开源免费，最强大的虚拟化工具

## 模板引擎

* [handlebars](https://github.com/wycats/handlebars.js) ⭐ 18,670 | 🐛 115 | 🌐 JavaScript | 📅 2026-06-24: mustache 的超集，支持复杂的语法和可扩展
* [art-template](https://github.com/aui/art-template) ⭐ 9,849 | 🐛 93 | 🌐 JavaScript | 📅 2026-07-13: 官宣性能最高的模板引擎
* [nunjucks](https://github.com/mozilla/nunjucks) ⭐ 8,990 | 🐛 361 | 🌐 JavaScript | 📅 2026-02-07: jinja2 inspired templating engine in nodejs
* [gomplate](https://github.com/hairyhenderson/gomplate) ⭐ 3,203 | 🐛 22 | 🌐 Go | 📅 2026-09-01: 用 Go 写的命令行工具
* [envsubst](https://www.gnu.org/software/gettext/manual/html_node/envsubst-Invocation.html): GNU 工具，`${VARIABLE}` 语法变量替换
  * [danday74/envsub](https://github.com/danday74/envsub) ⭐ 64 | 🐛 22 | 🌐 JavaScript | 📅 2025-08-10
* [mustache](http://mustache.github.io/): 简单变量替换用 mustache 即可。
* [lodash.template](https://lodash.com/docs/#template): 可以兼容各种模板变量语法，体积较小
* [Jinja](https://jinja.palletsprojects.com): Ansible 使用的模板引擎
  * [Jinja 模板在线渲染](https://cryptic-cliffs-32040.herokuapp.com)

## TeX/LaTeX

* [Typst](https://github.com/typst/typst) ⭐ 55,774 | 🐛 1,278 | 🌐 Rust | 📅 2026-09-01: latex 替代品。类似 markdown 语法，可以在文档内编程，Rust 渲染速度很快。
  * [tinymist](https://github.com/Myriad-Dreamin/tinymist) ⭐ 3,506 | 🐛 208 | 🌐 Rust | 📅 2026-08-31: language service for Typst
* [KaTeX](https://github.com/KaTeX/KaTeX) ⭐ 20,357 | 🐛 392 | 🌐 TypeScript | 📅 2026-08-31: Fast math typesetting for the web. <https://katex.org/>
* [Begin-Latex-in-minutes](https://github.com/luong-komorebi/Begin-Latex-in-minutes/blob/master/Translation-Chinese.md) ⚠️ Archived
* [awesome-LaTeX](https://github.com/egeerardyn/awesome-LaTeX) ⭐ 1,665 | 🐛 4 | 📅 2026-08-08
* [TEXMaker](https://www.xm1math.net/texmaker/)

## Slide/Presentation

* <https://slides.com/> : 基于 [reveal.js](https://github.com/hakimel/reveal.js) ⭐ 72,239 | 🐛 911 | 🌐 JavaScript | 📅 2026-08-24 的服务，非常好用，但是国内要翻墙 `ⱳ`
* [slidev](https://github.com/slidevjs/slidev) ⭐ 48,373 | 🐛 224 | 🌐 TypeScript | 📅 2026-08-25: <https://sli.dev/>
* [impress.js](https://github.com/impress/impress.js) ⭐ 38,169 | 🐛 59 | 🌐 JavaScript | 📅 2026-07-23: 类似 prezi.com 的 slide 框架
* [mdx-deck](https://github.com/jxnblk/mdx-deck) ⭐ 11,499 | 🐛 141 | 🌐 JavaScript | 📅 2023-01-04: 基于 MDX 写 slide
* [nodeppt](https://github.com/ksky521/nodeppt) ⚠️ Archived: 这可能是迄今为止最好的网页版演示库
* [spectacle](https://github.com/FormidableLabs/spectacle) ⭐ 10,158 | 🐛 75 | 🌐 TypeScript | 📅 2026-04-12: 基于 React 写的 slide
* [presenterm](https://github.com/mfontanini/presenterm) ⭐ 8,805 | 🐛 77 | 🌐 Rust | 📅 2026-05-22: 在终端播放 slide
  * [maaslalani/slides](https://github.com/maaslalani/slides) ⭐ 11,642 | 🐛 77 | 🌐 Go | 📅 2026-07-08: 备选方案
* [bespoke](https://github.com/bespokejs/bespoke) ⭐ 4,796 | 🐛 6 | 🌐 JavaScript | 📅 2020-09-08: DIY Presentation Micro-Framework

## SSG: Static Site Generator

* [next.js](https://github.com/vercel/next.js) ⭐ 142,047 | 🐛 3,535 | 🌐 JavaScript | 📅 2026-09-01: 「待评价」
* [Hugo](https://github.com/gohugoio/hugo) ⭐ 89,660 | 🐛 238 | 🌐 Go | 📅 2026-09-01: Go 生态。
* [docusaurus](https://github.com/facebook/docusaurus) ⭐ 66,141 | 🐛 399 | 🌐 TypeScript | 📅 2026-08-31: JS + React + MDX
* [astro](https://github.com/withastro/astro) ⭐ 62,208 | 🐛 98 | 🌐 TypeScript | 📅 2026-09-01: 「待评价」
* [gatsby](https://github.com/gatsbyjs/gatsby) ⭐ 55,943 | 🐛 438 | 🌐 JavaScript | 📅 2026-08-29: JS + React 生态。适合与 CMS、API、数据库搭配使用。
* [Gastby](https://github.com/gatsbyjs/gatsby) ⭐ 55,943 | 🐛 438 | 🌐 JavaScript | 📅 2026-08-29: 基于 React 和 GraphQL 的现代化静态网站生成器。可扩展性好。
  * [docz](https://github.com/doczjs/docz) ⚠️ Archived: 基于 MDX 和 Gastby 的，零配置的，文档生成器
* [docsify](https://github.com/docsifyjs/docsify) ⭐ 31,494 | 🐛 93 | 🌐 JavaScript | 📅 2026-08-28: 基于 Markdown 的文档生成器。在浏览器直接加载 Markdown 文档实时渲染。细节功能做得不是很理想。`routerMode: 'history'` 针对静态页面托管方案（比如 Github Pages）无效。
  * [docute](https://github.com/egoist/docute) ⚠️ Archived: 类似技术的备选方案
* [eleventy](https://github.com/11ty/eleventy) ⭐ 19,870 | 🐛 185 | 🌐 JavaScript | 📅 2026-08-31: 「待评价」
* [Zola](https://github.com/getzola/zola) ⭐ 17,388 | 🐛 190 | 🌐 Rust | 📅 2026-08-31: Rust 生态。自带搜索栏。
* [jekyll-theme-chirpy](https://github.com/cotes2020/jekyll-theme-chirpy) ⭐ 10,246 | 🐛 34 | 🌐 HTML | 📅 2026-07-30: 支持中文，TOC，搜索。
* [just-the-docs](https://github.com/just-the-docs/just-the-docs) ⭐ 9,146 | 🐛 98 | 🌐 SCSS | 📅 2026-08-25: 基于 Jekyll，适用于生成项目文档。搜索功能强大。
  * 缺点
    * `{:toc}` 这类语法依赖 kramdown，如果 \_config.yml 修改了 markdown 解析器，这类语法[将会失效](https://github.com/just-the-docs/just-the-docs/issues/1159) ⭐ 9,146 | 🐛 98 | 🌐 SCSS | 📅 2026-08-25。
    * 搜索栏默认[不支持中文](https://github.com/just-the-docs/just-the-docs/issues/59) ⭐ 9,146 | 🐛 98 | 🌐 SCSS | 📅 2026-08-25，它使用 [lunr.js](https://github.com/olivernn/lunr.js) ⭐ 9,201 | 🐛 130 | 🌐 JavaScript | 📅 2024-07-31，需要自己添加[语言包](https://github.com/MihaiValentin/lunr-languages) ⭐ 458 | 🐛 17 | 🌐 JavaScript | 📅 2026-08-09，得改很多东西。
    * 导航栏的编排很冗余。必须要给 markdown 文档加内容。
* [staticrypt](https://github.com/robinmoisson/staticrypt) ⭐ 8,025 | 🐛 33 | 🌐 HTML | 📅 2026-07-06: 加密静态网页，解密无需后端服务
* [bisheng](https://github.com/benjycui/bisheng) ⭐ 2,880 | 🐛 60 | 🌐 JavaScript | 📅 2023-09-26: 「待评价」
* [Jekyll](https://jekyllrb.com/): Ruby 生态。Github Page 默认 SSG。markdown 文本编译成网页。主题和插件生态非常丰富。
  * [jekyll-toc](https://github.com/allejo/jekyll-toc) ⭐ 522 | 🐛 0 | 🌐 Liquid | 📅 2024-01-15: 给 Github Page 的 jekyll 主题增加 TOC
  * [jekyll-remote-theme](https://github.com/benbalter/jekyll-remote-theme) ⭐ 334 | 🐛 12 | 🌐 Ruby | 📅 2026-08-31: 自动安装 jekyll 主题
  * [我的使用经验](https://til.adoyle.me/others/jekyll)
* [Hexo](https://hexo.io/): 适用于搭建个人博客。JS 生态。

### JAMstack

* [jamstack.org](https://github.com/jamstack/jamstack.org) ⭐ 3,036 | 🐛 138 | 🌐 Nunjucks | 📅 2026-04-08

## 文档

### 文档系统

* [AppFlowy](https://github.com/AppFlowy-IO/AppFlowy) ⭐ 76,161 | 🐛 1,015 | 🌐 Dart | 📅 2026-09-01: 类似 Notion 的笔记系统。基于 Flutter 和 Rust 开发
* [memos](https://github.com/usememos/memos) ⭐ 62,700 | 🐛 47 | 🌐 Go | 📅 2026-08-31: 轻笔记服务，功能类似 Flomo。简单好用易部署
* [outline](https://github.com/outline/outline) ⭐ 40,400 | 🐛 89 | 🌐 TypeScript | 📅 2026-09-01: 类似 Notion 的知识库、WIKI 平台
* [wiki.js](https://github.com/Requarks/wiki) ⭐ 28,825 | 🐛 190 | 🌐 Vue | 📅 2026-08-30: 现代化的 WIKI。AGPL-3.0 License
* [Tolaria](https://github.com/refactoringhq/tolaria) ⭐ 19,652 | 🐛 53 | 🌐 TypeScript | 📅 2026-08-30: 开源的 Markdown 笔记系统
* [scalar](https://github.com/scalar/scalar) ⭐ 16,025 | 🐛 67 | 🌐 TypeScript | 📅 2026-08-31: 根据 OpenAPI/Swagger 文件生成漂亮的 API 文档网站. <https://scalar.com/>
* [Obsidian](https://obsidian.md/): 笔记系统，纯 Markdown 文本数据本地存储，支持跨平台，插件生态好。用好插件才能发挥它的优势。
  * [quartz](https://github.com/jackyzha0/quartz) ⭐ 13,148 | 🐛 69 | 🌐 TypeScript | 📅 2026-08-18: Markdown 转静态网站
  * Obsidian 插件
    * [obsidian-git](https://github.com/Vinzent03/obsidian-git) ⭐ 11,892 | 🐛 131 | 🌐 TypeScript | 📅 2026-08-17: 定时保存修改到 git 并且同步到远端（可选）
    * [obsidian-copilot](https://github.com/logancyang/obsidian-copilot) ⭐ 7,658 | 🐛 121 | 🌐 TypeScript | 📅 2026-09-01: 集成 AI 到 obsidian
    * [Obsidian Tasks](https://github.com/obsidian-tasks-group/obsidian-tasks) ⭐ 3,978 | 🐛 156 | 🌐 TypeScript | 📅 2026-08-30: 使用 markdown 语法写任务管理
    * [Local REST API for Obsidian](https://github.com/coddingtonbear/obsidian-local-rest-api) ⭐ 2,877 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-31: 通过 HTTP API 操作 obsidian
    * [Advanced Tables](https://github.com/tgrosinger/advanced-tables-obsidian) ⭐ 2,600 | 🐛 111 | 🌐 TypeScript | 📅 2026-05-13: improved table navigation, formatting, and manipulation
    * [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) ⭐ 2,464 | 🐛 40 | 🌐 TypeScript | 📅 2026-07-13: 自定义 CSS
    * [Smart Composer](https://github.com/glowingjade/obsidian-smart-composer) ⭐ 2,322 | 🐛 112 | 🌐 TypeScript | 📅 2026-02-16: 集成 AI 到 obsidian，支持 Apply/Diff 操作
    * [Datacore](https://github.com/blacksmithgu/datacore) ⭐ 2,230 | 🐛 79 | 🌐 TypeScript | 📅 2026-06-22: dataview 的继任者。功能很强大。使用 JS/JSX 编辑视图，不支持 DQL。还在开发中
    * [obsidian-importer](https://github.com/obsidianmd/obsidian-importer) ⭐ 1,635 | 🐛 62 | 🌐 TypeScript | 📅 2026-08-26: import notes from other apps and file formats into your Obsidian
    * [brat](https://github.com/TfTHacker/obsidian42-brat) ⭐ 1,627 | 🐛 23 | 🌐 TypeScript | 📅 2026-08-20: 用于安装开发中插件的插件管理器
    * [Editing Toolbar](https://github.com/PKM-er/obsidian-editing-toolbar) ⭐ 1,519 | 🐛 152 | 🌐 TypeScript | 📅 2026-08-13: 置顶工具栏, 光标跟随工具栏
    * [Advanced Canvas](https://github.com/Developer-Mike/obsidian-advanced-canvas) ⭐ 1,505 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-28
    * [obsidian-minimal-settings](https://github.com/kepano/obsidian-minimal-settings) ⭐ 803 | 🐛 10 | 🌐 TypeScript | 📅 2026-07-31: 简单好用的主题
    * [obsidian-homepage](https://github.com/mirnovov/obsidian-homepage) ⭐ 711 | 🐛 22 | 🌐 TypeScript | 📅 2026-06-03: 启动 obsidian 后自动打开主页文档
    * [Auto Link Title](https://github.com/zolrath/obsidian-auto-link-title) ⭐ 697 | 🐛 90 | 🌐 TypeScript | 📅 2024-12-15: 从粘贴的链接中自动获取标题
    * [Numerals](https://github.com/gtg922r/obsidian-numerals) ⭐ 642 | 🐛 42 | 🌐 TypeScript | 📅 2026-07-18: power of an advanced calculator inside a math code block, complete with currencies, units, variables, and math functions!
    * [Code Styler Plugin](https://github.com/mayurankv/Obsidian-Code-Styler) ⭐ 602 | 🐛 122 | 🌐 JavaScript | 📅 2025-02-16: lets you style codeblocks and inline code in both editing mode and reading mode.
    * [Obsidian List Callouts](https://github.com/mgmeyers/obsidian-list-callouts) ⭐ 494 | 🐛 65 | 🌐 TypeScript | 📅 2024-09-08
    * [Image Auto Upload](https://github.com/renmu123/obsidian-image-auto-upload-plugin) ⭐ 473 | 🐛 78 | 🌐 TypeScript | 📅 2024-11-28: 配合 picgo 实现图片自动上传到图床。需要仔细配置才能用好。
    * [Whisper Obsidian Plugin](https://github.com/nikdanilov/whisper-obsidian-plugin) ⭐ 376 | 🐛 15 | 🌐 TypeScript | 📅 2026-04-07: Speech-to-text in Obsidian using OpenAI Whisper
    * [Canvas MindMap](https://github.com/Quorafind/Obsidian-Canvas-MindMap) ⭐ 374 | 🐛 24 | 🌐 TypeScript | 📅 2024-09-04: [该插件与 Smart Composer 有冲突](https://github.com/Quorafind/Obsidian-Canvas-MindMap/issues/71) ⭐ 374 | 🐛 24 | 🌐 TypeScript | 📅 2024-09-04
    * [Front Matter Title](https://github.com/snezhig/obsidian-front-matter-title) ⭐ 372 | 🐛 7 | 🌐 TypeScript | 📅 2026-08-28: 用元数据 title 作为文件标题
    * [Obsidian Columns](https://github.com/tnichols217/obsidian-columns) ⭐ 299 | 🐛 28 | 🌐 TypeScript | 📅 2024-11-30: 多列显示。支持移动端 OB
    * [obsidian-floating-toc-plugin](https://github.com/cumany/obsidian-floating-toc-plugin) ⭐ 287 | 🐛 58 | 🌐 TypeScript | 📅 2026-01-24: 浮动 table of content
    * [obsidian-douban](https://github.com/Wanxp/obsidian-douban) ⭐ 271 | 🐛 28 | 🌐 TypeScript | 📅 2026-08-17: 从豆瓣抓取书影音等信息
    * [pixel-banner](https://github.com/jparkerweb/pixel-banner) ⭐ 211 | 🐛 31 | 🌐 JavaScript | 📅 2026-04-17: 给文章增加 banner
    * [obsidian-frontmatter-modified-date](https://github.com/alangrainger/obsidian-frontmatter-modified-date) ⭐ 172 | 🐛 7 | 🌐 TypeScript | 📅 2026-05-27: 自动创建、修改 created 和 modified 时间
    * [Update modified field on edit](https://github.com/alangrainger/obsidian-frontmatter-modified-date) ⭐ 172 | 🐛 7 | 🌐 TypeScript | 📅 2026-05-27
    * [Image Captions](https://github.com/alangrainger/obsidian-image-captions) ⭐ 168 | 🐛 23 | 🌐 TypeScript | 📅 2026-08-30: 让图片显示标注
    * [Slash Commander](https://github.com/alephpiece/obsidian-slash-commander) ⭐ 111 | 🐛 11 | 🌐 TypeScript | 📅 2026-08-03: 按 / 显示快捷命令列表，可自定义
    * [Trash Explorer](https://github.com/proog/obsidian-trash-explorer) ⭐ 72 | 🐛 12 | 🌐 TypeScript | 📅 2026-01-10: Restore and delete files from the Obsidian .trash folder
    * [Trim Whitespace](https://github.com/zlovatt/obsidian-trim-whitespace) ⭐ 63 | 🐛 11 | 🌐 TypeScript | 📅 2026-08-29: 去除多余空格
    * [Vim Toggle](https://github.com/conneroisu/vim-toggle) ⭐ 47 | 🐛 12 | 🌐 TypeScript | 📅 2025-11-15: 让 obsidian 支持 vim 快捷键
    * [obsidian-file-cleaner](https://github.com/johnsonhong997/obsidian-file-cleaner) ⭐ 46 | 🐛 14 | 🌐 TypeScript | 📅 2023-11-05: 清理空文件和不需要的附件
    * [Show Whitespace](https://github.com/ebullient/obsidian-show-whitespace-cm6) ⭐ 43 | 🐛 7 | 🌐 TypeScript | 📅 2026-08-31: 显示换行符和多余的空格
    * [Market Proxy](https://github.com/haierkeys/obsidian-market-proxy) ⭐ 38 | 🐛 1 | 🌐 TypeScript | 📅 2026-03-02
    * [Refresh Any View](https://github.com/mnaoumov/obsidian-refresh-any-view) ⭐ 28 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-01: 增加一个刷新页面的按钮
    * 不要安装 make.md，它可能会把你的文档数据弄丢！
  * Obsidian css snippets
    * [Dmytro-Shulha/obsidian-css-snippets](https://github.com/Dmytro-Shulha/obsidian-css-snippets) ⭐ 1,752 | 🐛 5 | 📅 2024-12-15
    * [r-u-s-h-i-k-e-s-h/Obsidian-CSS-Snippets](https://github.com/r-u-s-h-i-k-e-s-h/Obsidian-CSS-Snippets) ⭐ 1,547 | 🐛 0 | 📅 2026-07-22
    * [Obsidian-Colored-Sidebar](https://github.com/CyanVoxel/Obsidian-Colored-Sidebar) ⭐ 854 | 🐛 20 | 🌐 CSS | 📅 2024-05-17: A Colored Sidebar CSS Snippet for Obsidian.
    * [gsarig/obsidian-css-snippets](https://github.com/gsarig/obsidian-css-snippets) ⭐ 158 | 🐛 0 | 🌐 CSS | 📅 2026-05-05
* [Notion](https://www.notion.so/): 笔记工具
  * <https://timelinetool.app/notion/event> : 统计公开链接的 PV 的 embed 插件
* 基于 Notion 的网站
  * <https://popsy.co/> : 自定义域名免费。收费功能 8 刀/月
  * <https://super.so/> : 用户体验优秀。自定义域名收费。收费功能 12 刀/月
* 基于 Notion 自建网站
  * [nextjs-notion-starter-kit](https://github.com/transitive-bullshit/nextjs-notion-starter-kit) ⭐ 7,029 | 🐛 151 | 🌐 TypeScript | 📅 2026-08-26
  * [notion-sdk-js](https://github.com/makenotion/notion-sdk-js) ⭐ 5,655 | 🐛 72 | 🌐 TypeScript | 📅 2026-08-31
  * [react-notion-x](https://github.com/NotionX/react-notion-x) ⭐ 5,431 | 🐛 181 | 🌐 TypeScript | 📅 2026-08-24: 用 react 组件搭建 notion page
  * [notion-blog](https://github.com/ijjk/notion-blog) ⭐ 3,858 | 🐛 27 | 🌐 TypeScript | 📅 2024-04-08
* [sphinx-doc](https://www.sphinx-doc.org): reStructuredText 文档渲染工具

### 文档处理

* [carbon](https://github.com/dawnlabs/carbon) ⭐ 36,083 | 🐛 85 | 🌐 JavaScript | 📅 2026-02-10: 代码转成图片
* [unified](https://github.com/unifiedjs/unified) ⭐ 5,027 | 🐛 1 | 🌐 JavaScript | 📅 2026-04-29: interface for parsing, inspecting, transforming, and serializing content through syntax trees
* [盤古之白](https://github.com/vinta/pangu.js) ⭐ 4,811 | 🐛 6 | 🌐 TypeScript | 📅 2026-08-31: 给文档加空格
  * <https://github.com/vinta/pangu.space> ⭐ 29 | 🐛 0 | 🌐 HCL | 📅 2026-02-10 : Web API
* [rehype](https://github.com/rehypejs/rehype) ⭐ 2,252 | 🐛 1 | 🌐 JavaScript | 📅 2026-06-13: HTML processor
* [pandoc](https://pandoc.org/): 各种格式的文档转换工具 <a name="unified"></a>

### 文档检查

* [lychee](https://github.com/lycheeverse/lychee) ⭐ 3,878 | 🐛 76 | 🌐 Rust | 📅 2026-08-31: 命令行工具，检查文档中的链接和邮件地址是否有效
  * [markdown-link-check](https://github.com/tcort/markdown-link-check) ⭐ 712 | 🐛 13 | 🌐 JavaScript | 📅 2026-07-28: 备用方案。没人维护。JS 写的
  * [lychee-action](https://github.com/lycheeverse/lychee-action) ⭐ 510 | 🐛 11 | 🌐 Shell | 📅 2026-07-09: 用 github action 自动检查

### 文档排版

* [中文文案排版指北](https://github.com/sparanoid/chinese-copywriting-guidelines) ⭐ 15,667 | 🐛 30 | 📅 2026-07-07
* [赫蹏（hètí）](https://github.com/sivan/heti) ⭐ 6,720 | 🐛 24 | 🌐 SCSS | 📅 2025-08-31: css 样式
* [中文排版需求](https://www.w3.org/TR/clreq/)
  * <https://github.com/w3c/clreq> ⭐ 807 | 🐛 187 | 🌐 HTML | 📅 2026-08-21

### Markdown

* [mdx](https://github.com/mdx-js/mdx) ⭐ 19,763 | 🐛 20 | 🌐 JavaScript | 📅 2026-08-31: Markdown + JSX = MDX。支持模块导入和导出，支持 React 组件。写 Web 文档利器。
  * [Code Hike](https://github.com/code-hike/codehike) ⭐ 5,376 | 🐛 19 | 🌐 TypeScript | 📅 2026-03-17: MDX 的 remark 插件。使用场景：code walkthrough。
* [remark](https://github.com/remarkjs/remark) ⭐ 8,992 | 🐛 12 | 🌐 JavaScript | 📅 2026-07-01: markdown processor
* [markdown-toc](https://github.com/jonschlinkert/markdown-toc) ⭐ 1,756 | 🐛 91 | 🌐 JavaScript | 📅 2024-08-09: 根据 markdown heading 文本输出 TOC
* [json2md](https://github.com/IonicaBizau/json2md) ⭐ 653 | 🐛 8 | 🌐 JavaScript | 📅 2025-04-11: 非常灵活的 Markdown 生成工具，容易自己定制功能
* [unified](#unified)
  * [marked](https://github.com/markedjs/marked) ⭐ 37,110 | 🐛 25 | 🌐 JavaScript | 📅 2026-08-31: 备用方案

### Markdown 编辑器

* [marktext](https://github.com/marktext/marktext) ⭐ 60,866 | 🐛 733 | 🌐 TypeScript | 📅 2026-09-01: 跨平台的 Markdown 编辑器，GUI 应用
* [stackedit](https://github.com/benweet/stackedit) ⭐ 23,079 | 🐛 732 | 🌐 JavaScript | 📅 2023-07-04: 运行在浏览器中的 Markdown 编辑器。文件存储在浏览器的 localstorage 中，也可以导出到文本到本地磁盘、Google Drive、Dropbox，或你的 GitHub 账户下。详见[链接](https://github.com/benweet/stackedit/blob/6dce2a5e36b755a0c244522b48a06c91a2df0f59/src/data/welcomeFile.md) ⭐ 23,079 | 🐛 732 | 🌐 JavaScript | 📅 2023-07-04。

### Changelog

* [standard-version](https://github.com/conventional-changelog/standard-version) ⭐ 7,978 | 🐛 309 | 🌐 JavaScript | 📅 2026-07-16: Automate versioning and CHANGELOG generation, with semver.org and conventionalcommits.org (现在无人维护)
  * [semantic-release](https://github.com/semantic-release/semantic-release) ⭐ 24,012 | 🐛 403 | 🌐 JavaScript | 📅 2026-08-29: 备选方案
  * conventional-changelog 的 [.versionrc 配置](https://github.com/conventional-changelog/conventional-changelog-config-spec/) ⭐ 125 | 🐛 28 | 🌐 JavaScript | 📅 2026-08-31
* [release-please](https://github.com/googleapis/release-please) ⭐ 7,427 | 🐛 351 | 🌐 TypeScript | 📅 2026-08-24: 结合 Github Action 自动执行：生成 Changelog，打 tag，发 Release
* [git-chglog](https://github.com/git-chglog/git-chglog) ⚠️ Archived: CHANGELOG generator implemented in Go
* <http://keepachangelog.com/>  Changelog 书写规约

## Hash

* [xxHash](https://github.com/Cyan4973/xxHash) ⭐ 11,231 | 🐛 42 | 🌐 C | 📅 2026-07-27
* [Wikipedia - List of hash functions](https://www.wikiwand.com/en/List_of_hash_functions)
* [hashids](https://hashids.org/)

## [图像处理](./picture/README.md)

## 视频处理

* [Remotion](https://github.com/JonnyBurger/remotion) ⭐ 57,939 | 🐛 170 | 🌐 TypeScript | 📅 2026-09-01: 用 React 制作视频

## 压缩/解压

* [zstd](https://github.com/facebook/zstd) ⭐ 27,652 | 🐛 354 | 🌐 C | 📅 2026-09-01: 压缩比率、速度都很高。
* [snappy](https://github.com/google/snappy) ⭐ 6,602 | 🐛 65 | 🌐 C++ | 📅 2026-07-31: 速度非常快，但压缩比低。
* [mozjpeg](https://github.com/mozilla/mozjpeg) ⭐ 5,719 | 🐛 102 | 🌐 C | 📅 2025-06-23: mozilla 出品的 JPEG 图像压缩算法，压缩率很高

## [OCR](./ML/README.md#ocr)

## [Android](./android/README.md)

## 截图/录屏

* [PixPin](https://pixpinapp.com/): 免费的截图/截屏工具，支持长截图，GIF 截图，录屏，颜色提取，标注，OCR（先截图，固定到屏幕，然后复制图片文字）。支持保存 webp 格式。 `ⓦ` `Ⓜ`
* [CleanShot X](https://cleanshot.com/): 用户体验很优秀。价格略贵，按年付费。支持截图/窗口截图/截屏/滚动截屏/录屏/录音/OCR 识别/标注。 `Ⓜ`
* [Shottr](https://shottr.cc/): 功能很丰富，可以代替 CleanShot X，价格适中，一次性买断。 `Ⓜ`
* [Monosnap](https://monosnap.com/welcome): 免费又强大的截图/截屏/录屏(支持 GIF 和 MP4)。不支持滚动截屏。 <a name="Monosnap"></a>
* Mac 系统自带截图工具。不支持滚动截屏，其他功能都有。Safari 支持滚动截屏。
* screencapture:  Mac 自带命令，截图/截屏工具。
* [ShareX](https://getsharex.com/): 开源的截图、截屏、录屏、颜色提取、OCR、滚动截图。交互设计一般 `ⓦ`
* [kap](https://github.com/wulkano/kap/) ⭐ 19,343 | 🐛 254 | 🌐 TypeScript | 📅 2024-11-12: 用户体验很好的，开源的录屏工具，支持 GIF, MP4, WebM, APNG `Ⓜ` `⨀`

## 漫画

* [mihon](https://github.com/mihonapp/mihon) ⭐ 23,280 | 🐛 726 | 🌐 Kotlin | 📅 2026-08-30: 看漫画用的，需要导入插件订阅第三方源。
  * [Keiyoushi Extensions](https://github.com/keiyoushi/extensions) ⭐ 14,853 | 🐛 0 | 🌐 HTML | 📅 2026-09-01: Extension repository for Mihon and variants
  * [copymanga-copy20](https://github.com/LittleSurvival/copymanga-copy20) ⭐ 2,668 | 🐛 15 | 🌐 Smali | 📅 2026-08-23
  * [Kahon](https://github.com/AmanoTeam/Kahon) ⭐ 323 | 🐛 5 | 🌐 Kotlin | 📅 2026-08-29: A fork of Mihon with some annoying restrictions removed
* [Suwayomi-Server](https://github.com/Suwayomi/Suwayomi-Server) ⭐ 7,535 | 🐛 178 | 🌐 Java | 📅 2026-08-30: 自部署的漫画服务。界面类似 mihon，兼容 mihon 插件和源。支持 docker 部署。
  * [tachiyomi-extension](https://github.com/Suwayomi/tachiyomi-extension) ⭐ 317 | 🐛 14 | 🌐 Kotlin | 📅 2026-08-29: Mihon 插件，访问 Suwayomi server

## 视频/音频

* [jellyfin](https://github.com/jellyfin/jellyfin) ⭐ 56,425 | 🐛 597 | 🌐 C# | 📅 2026-08-31: 多媒体系统。可以看电源和图片。支持 docker 自部署、IPTV、硬解、外挂字幕。UI 颜值不错。
  * [awesome-jellyfin](https://github.com/awesome-jellyfin/awesome-jellyfin) ⭐ 9,115 | 🐛 40 | 🌐 Shell | 📅 2026-08-31: jellyfin 开源生态
  * [jellyfin-plugin-metashark](https://github.com/cxfksword/jellyfin-plugin-metashark) ⭐ 2,127 | 🐛 3 | 🌐 C# | 📅 2026-08-06: 电影元数据插件，数据来自豆瓣
  * [jellyfin-plugin-bangumi](https://github.com/kookxiang/jellyfin-plugin-bangumi) ⭐ 1,129 | 🐛 28 | 🌐 C# | 📅 2026-08-20: 动漫元数据插件，数据来自 bangumi
  * [jellyfin-plugin-skin-manager](https://github.com/danieladov/jellyfin-plugin-skin-manager) ⭐ 660 | 🐛 42 | 🌐 JavaScript | 📅 2026-05-05: 皮肤管理器
* [iina](https://github.com/lhc70000/iina) ⭐ 46,167 | 🐛 1,914 | 🌐 Swift | 📅 2026-09-01: 视频播放器。基于 [mpv][] 开发 `Ⓜ`
* [mpv](https://github.com/mpv-player/mpv) ⭐ 36,799 | 🐛 1,148 | 🌐 C | 📅 2026-08-31: 跨平台的媒体播放器，支持命令行
  * [vlc](https://github.com/videolan/vlc) ⭐ 19,499 | 🐛 2 | 🌐 C | 📅 2026-09-01: 备选方案
* [HandBrake](https://github.com/HandBrake/HandBrake) ⭐ 24,240 | 🐛 296 | 🌐 C | 📅 2026-08-31: 视频转码器
* [obs-ndi](https://github.com/Palakis/obs-ndi) ⭐ 4,522 | 🐛 63 | 🌐 C++ | 📅 2026-08-23: 采集窗口的视频和音频
* [µStreamer](https://github.com/pikvm/ustreamer) ⭐ 2,027 | 🐛 11 | 🌐 C | 📅 2026-08-29: 轻量级的 MJPEG 转 HTTP 推流服务。支持 VGA 和 HDMI 采集卡。
* [OBS](https://obsproject.com/): 非常好用的推流和录制工具。免费。
  * [源码 obsproject/obs-studio](https://github.com/obsproject/obs-studio) ⭐ 75,692 | 🐛 1,174 | 🌐 C | 📅 2026-08-26
* [Sound Siphon](https://staticz.com/soundsiphon/): Mac 下最好用的音频录制工具。能创建虚拟输入设备。能把任何应用的音频输出转发到另一个应用上。价格有点贵。 `Ⓜ`
  * [BlackHole](https://github.com/ExistentialAudio/BlackHole) ⭐ 19,665 | 🐛 12 | 🌐 C | 📅 2026-08-11: 免费的开源方案
  * [loopback](https://rogueamoeba.com/loopback/): 类似的备选方案，价格更贵 `Ⓜ`
  * [Audio Hijack](https://rogueamoeba.com/audiohijack/): 专业录音工具。不能创建虚拟设备。 `Ⓜ`
* [forecast](https://overcast.fm/forecast): MP3 metadata 编辑器。做播客会用到。 `Ⓜ` <a name="mpv"></a>
* [ffmpeg](https://ffmpeg.org/): 非常强大的视音频处理软件。命令行或者 API 编程用。

### 音乐

* [SpotX](https://github.com/SpotX-Official/SpotX) ⭐ 22,205 | 🐛 3 | 🌐 PowerShell | 📅 2026-08-31: 修改 Spotify，屏蔽广告，只对 Windows 平台有效。
  * [SpotX-Bash](https://github.com/SpotX-Official/SpotX-Bash) ⭐ 5,990 | 🐛 3 | 🌐 Shell | 📅 2026-08-27: 修改 Spotify，屏蔽广告，只对 Linux、MacOS 有效。
* [MuseScore](https://github.com/musescore/MuseScore) ⭐ 15,042 | 🐛 4,158 | 🌐 C++ | 📅 2026-09-01: 开源的打谱软件
* <https://musescore.com/> : MuseScore 曲谱分享平台。包含可视化弹奏等强大功能。大部分功能收费。
* <http://etaaudio.com/> : 遵循 CC 协议分享的音乐库

## 知识图谱

## 互联网关键词趋势

* [Google Trends](https://trends.google.com/trends/)

## [机器学习](./ML/README.md)

## 运营

* [Wechatsync](https://github.com/wechatsync/Wechatsync) ⭐ 6,250 | 🐛 37 | 🌐 TypeScript | 📅 2026-05-27: 一键多平台同步发布文章。支持微信公众号、知乎、微博、今日头条、BiliBili、WordPress、简书、掘金、typecho 等平台
* <https://lab.lyric.im/wxformat/> : Markdown 转微信公众号排版的工具
  * [源码](https://github.com/lyricat/wechat-format) ⭐ 4,549 | 🐛 4 | 🌐 JavaScript | 📅 2025-09-13

## [中国特色](./for-china.md)

## [人文](./humanities.md)

## [Funny](./funny.md)

## 游戏开发

* [godot](https://github.com/godotengine/godot) ⭐ 116,475 | 🐛 18,823 | 🌐 C++ | 📅 2026-08-31: 免费的游戏引擎。MIT License
* [cheat-engine](https://github.com/cheat-engine/cheat-engine/) ⭐ 19,095 | 🐛 1,307 | 🌐 Pascal | 📅 2025-04-19: 游戏内存修改器。支持 Mac。
* [godot-lang-support](https://github.com/Vivraan/godot-lang-support) ⭐ 563 | 🐛 0 | 📅 2026-06-30: godot 其他编程语言扩展

## 二维码

* [zxing](https://github.com/zxing/zxing) ⭐ 34,078 | 🐛 6 | 🌐 Java | 📅 2026-08-31: 开源的二维码扫描工具，提供类库以及安装包，支持 Android、iOS。
* [qrcode](https://github.com/soldair/node-qrcode) ⭐ 8,164 | 🐛 125 | 🌐 JavaScript | 📅 2024-08-23: 命令行版二维码生成器
* [二维码生成器](https://qrbtf.com/)

## FTP

* [vsftpd](https://security.appspot.com/vsftpd.html): Very Secure FTP Daemon
* [uftp](https://uftp-multicast.sourceforge.net/): 基于 UDP 的 FTP 服务器和客户端
* [ncftp](https://www.ncftp.com/ncftp/): ftp 命令行客户端，macos、linux 平台通用。缺点是不支持 ftp over ssl。
  * [lftp](https://lftp.yar.ru): macos、linux 平台通用。支持 ftp over TLS or OpenSSL。缺点是没有 lls 这样的指令。只能用 `!`。
* [Transmit](https://panic.com/transmit/): FTP/SFTP/WebDAV/S3/Backblaze B2/Box/Google Drive/DreamObjects/Dropbox/Microsoft Azure/Rackspace Cloud Files 客户端 APP。 `Ⓜ`
* [sftpgo](https://github.com/drakkan/sftpgo) ⭐ 12,472 | 🐛 173 | 🌐 Go | 📅 2026-08-31: Full-featured and highly configurable SFTP, HTTP/S, FTP/S and WebDAV server
* [WinSCP](https://winscp.net/): 免费开源的 FTP GUI 客户端。也支持 SCP、WebDAV、S3。支持中文文件名。`ⓦ`
* [muCommander](https://www.mucommander.com/): 开源、跨平台的 FTP GUI 客户端。支持 FTP, SFTP, SMB, NFS, HTTP, Amazon S3, Hadoop HDFS, Bonjour。缺点：中文文件名会显示乱码。

## 资讯/信息

* [TrendRadar](https://github.com/sansan0/TrendRadar) ⭐ 61,977 | 🐛 59 | 🌐 Python | 📅 2026-07-17: 用 AI 筛选聚合资讯的平台

### RSS

* [RSSHub](https://github.com/DIYgod/RSSHub) ⭐ 45,970 | 🐛 357 | 🌐 TypeScript | 📅 2026-09-01: 从任何内容生成 RSS/Atom/JSON 订阅源。定制转换路由需要自己写 JS 代码，略麻烦。
* [RSSHub-Radar](https://github.com/DIYgod/RSSHub-Radar) ⭐ 7,320 | 🐛 70 | 🌐 TypeScript | 📅 2026-09-01: 浏览器插件，用于查询 RSS 或 RSSHub 订阅
* [TTRSS](https://github.com/HenryQW/Awesome-TTRSS) ⭐ 2,597 | 🐛 1 | 🌐 PHP | 📅 2026-08-07: 自部署的 RSS 阅读器 Web 服务

***

## 别人的工具列表

* [Kickball/awesome-selfhosted](https://github.com/Kickball/awesome-selfhosted) ⭐ 316,443 | 🐛 0 | 📅 2026-09-01
* [jaywcjlove/awesome-mac](https://github.com/jaywcjlove/awesome-mac/blob/master/README-zh.md) ⭐ 112,260 | 🐛 775 | 🌐 Swift | 📅 2026-09-01
* [sbilly/awesome-security](https://github.com/sbilly/awesome-security) ⭐ 14,817 | 🐛 320 | 📅 2026-01-11
* [skyseraph/Soft-Tools](https://github.com/skyseraph/Soft-Tools) ⭐ 306 | 🐛 0 | 📅 2026-04-23

<!-- anchors -->

[KeePass]: #user-content-KeePass

[PlantUML]: #user-content-PlantUML

[Homebrew]: #user-content-Homebrew

[mpv]: #user-content-mpv

[commitlint]: #user-content-commitlint

<!-- links -->

[LICENSE]: ./LICENSE

[NOTICE]: ./NOTICE

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-01._
