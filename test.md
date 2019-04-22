##### Git 的一些基本操作

​	1.git add  文件名   将变更的文件添加至暂存区

​	2.git commit -m "提交描述"  将变更的文件提交到工作区

​	3.git status 查看状态

​	4.git pull  从远端仓库更新

​	5.git push 提交到远端仓库

​	6.git log 查看提交日志

​	7.git log --pretty=short   查看提交日志，这个和git log 的区别是，git log --pretty=short 不显示提交时间，其余都一样

​	8.git log 目录名|文件名  对应的只显示该目录或者与该文件相关的日志

​	9. git log -p  查看提交文件前后的差别该变

##### Git 分支介绍

​	1.git branch  既可以显示当前分支列表，又可以显示当前所在分支

​	2.git checkout -b  分支名     创建本地分支

​	3.git checkout  切换分支

​	4.git checkout -  切换回上一个分支

​	5.不断对一个分支进行提交的操作，称之为"培育分支"

​	6.通常我们会用 master 分支作为主干分支，主干分支并没有开发到一半的代码，可以随时供他人查看。

​	7.有时我们需要让这个主干分支总是配置在正式环境中，有时又需要用标签Tag等创建版本信息，同时管理多个版本发布。拥有多个版本发布时，主干分支也有多个。

##### Git 分支上的一些操作

​	1.git merge --no-ff  分支名   合并分支前，首先切换到master 分支上。

​	2.git log --graph  以图表形式查看分支

​	3. git reset  回溯历史版本





