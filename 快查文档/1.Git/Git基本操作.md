<<<<<<< HEAD
# Git基本操作

*Git 是一个开源的分布式版本控制系统，用于敏捷高效地处理任何或小或大的项目。*

### 工作原理

![img](Git基本操作.assets/git-command.jpg)

##### **说明：**

- workspace：工作区
- staging area：暂存区/缓存区
- local repository：版本库或本地仓库
- remote repository：远程仓库

### 常用指令

--git clone、git push、git add 、git commit、git checkout、git pull

| 命令名称                         | 作用                         |
| -------------------------------- | ---------------------------- |
| git config  --global user.name   | 用户名 设置用户签名          |
| git config  --global user.email | 邮箱 设置用户签名            |
| **版本相关命令**                 |                              |
| git init                         | 初始化本地库                 |
| git status                       | 查看本地库状态               |
| git add . \| file1 file2 \| dir | 将当前目录下所有文件 \| 指定文件 \| 指定文件夹添加到暂存区 |
| git commit -m  "日志信息" 文件名 | 提交到本地库                 |
|  git reset						|将暂存区的文件取消暂存或是切换到指定分支|
| git reflog                       | 查看历史记录                 |
| git reset --hard 版本号          | 版本穿梭                     |
|git log|查看日志|
| **分支相关命令**                 |                              |
| git  branch 分支名 | 创建分支                     |
| git branch -v -r -a              | 查看分支 -v 显示最新日志 -r远程仓库的地址分支 -a 本地远程所有分支 |
| git  checkout 分支名             | 切换分支                     |
| git  merge 分支名                | 把指定的分支合并到当前分支上 |
|                                  |                              |




| **远程仓库操作**                                |                                                          |
| ----------------------------------------------- | -------------------------------------------------------- |
| git remote -v                                   | 查看当前所有远程地址别名                                 |
| git  remote add 别名 远程地址                   | 起别名                                                   |
| git push <远程主机名> <本地分支名>:<远程分支名> | 推送本地分支上的内容到远程仓库                           |
| git  clone 远程地址                             | 将远程仓库的内容克隆到本地                               |
| git  pull 远程库地址别名 远程分支名             | 将远程仓库对于分支最新内容拉下来后与当前本地分支直接合并 |
|                                                 |                                                          |
