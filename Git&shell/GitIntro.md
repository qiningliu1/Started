# Git Introduction

##  
# 主题：Git & Shell

## 日期：2024-04-21
## 注意事项
这部分知识比较抽象

## 目标

- 为什么要使用Git
- 如何设置Git
- Git的本地工作方法
- 使用Git branch进行创建与合并分支
- 使用GitHub进行团队协作

## 1. Introduction
### 1.1  为什么要使用Version Control
1. 撤销改动或者回滚版本
-
-
2. 回溯历史


3. 协同合作
    
4. 备份




## 2. Git简介
#### 2.1 Git安装配置
- git and GitHub
- git Global Setup

#### 2.2 Setting up a repository
- git init 这个指令可以再终端初始化（Vs code中）
- git Clone (remote repository only)

#### 2.3 Git的三个分区
- 工作目录working directory
    操作系统上的文件，所有代码开发编辑都在上面完成
- 索引index or staging area
    一个暂存区域，会在下一次commit被提交到Git仓库
- Git仓库git repository
    由Git object记录着每一次提交的快照，以及链式结构记录的提交变更历史


#### 2.4 Git工作原理
- 两步 commit
    操作系统上的文件，所有代码开发编辑都在上面完成
- Commit message要有意义
    一个暂存区域，会在下一次commit被提交到Git仓库
- Git仓库git repository
    由Git object记录着每一次提交的快照，以及链式结构记录的提交变更历史

#### 2.5 Git Status and history
- git status：可以让我们时刻掌握仓库当前的状态
    操作系统上的文件，所有代码开发编辑都在上面完成
- git diff：查看工作区和版本库里面最新版本的区别
    一个暂存区域，会在下一次commit被提交到Git仓库
- git log：查看从最近到最远的提交日志
   
#### 2.6 Git 
- git status：可以让我们时刻掌握仓库当前的状态
    操作系统上的文件，所有代码开发编辑都在上面完成
- git diff：查看工作区和版本库里面最新版本的区别
    一个暂存区域，会在下一次commit被提交到Git仓库
- git log：查看从最近到最远的提交日志





### Node.js安装
在markdown中插入图片的语法是

![替代文本](图片链接 "可选的标题")

-1.我的报错解决方案
![Node.js安装错误](Installmethod.png "安装错误截图")
先搜索powershell，再右键选择管理员身份打开
通过在左下角window图标右键管理员




## 1. 变量和数据类型

JavaScript 提供了多种数据类型来存储不同类型的数据：

- **字符串 (String)**
- **数字 (Number)**
- **布尔值 (Boolean)**

### 示例代码

```javascript
let name = "John Doe"; // 字符串
let age = 30; // 数字
let isDeveloper = true; // 布尔值
```
## 2. 函数

函数是执行特定任务的代码块。在 JavaScript 中，函数可以如下定义：

```javascript
function greet(name) {
    console.log("Hello, " + name + "!");
}

greet("John");
```


记得在实际使用时，将代码块的 ``` 符号用来包围实际的代码片段，而不是作为模板的一部分。希望这个模板能帮助你开始在 VS Code 中高效地记录笔记！