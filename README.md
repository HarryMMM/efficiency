## 简介

本工具是为了提高工作效率，开发的一系列脚本。目前只在Windows上工作。

## 准备工作
- 安装Git软件，目的是执行shell脚本。

## 开始

### 初始化honey系统
进入根目录，执行init脚本
```
sh init
```
### 使用
此时你可以使用efficiency/bin中的脚本了

## 工程目录结构

```
EFFICIENCY
│  .gitignore
│  init                                         #初始化脚本
│  README.md
│
├─bin
│  ├─common                                     #公共工具
│  │      directory_tools
│  │      log_printer
│  │      string_tools
│  │
│  ├─git                                        #git脚本
│  │      gc
│  │
│  ├─init                                       #初始化脚本
│  │      01_constant_init
│  │      02_register_init
│  │
│  └─system                                     honey系统管理脚本
│          honey
│
├─config                                        #配置目录
│  ├─custom                                     #系统配置目录
│  │      profile
│  │
│  └─system                                     #用户自定义配置目录
│          profile
│
└─log                                           #日志目录
    
```