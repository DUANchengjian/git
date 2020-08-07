# readme

<<<<<<< HEAD
+  项目说明文档
=======
+项目说明文档-duan
更新的
>>>>>>> 3677ca7a4e4d845c859b97f9bb75a81ea3267053


## git init
1. 把当前目录初始化为版本库
2. 当前目录下生成一个隐藏文件.git


# git add 文件名
1. 把当前目录下的某个文件提交到暂存区
2. git add

# git status
1. 查看当前目录状态（新增、删除、修改）

# git commit -m '提交注释'
1. 把暂存区的内容提交到本地仓库 

## 本地仓库的三个组成部分
1. 工作区（实际持有文件）
2. 暂存区
3. 本地仓库

## git log
1. 查看操作日志

## git reflg
1. 查看操作日志（简单版）

## git  diff 文件名
1. 查看文件变更信息

## git reset --hard 版本号（操作日志可以查看）

1. 版本回退 HEAD^回退到上个版本
2. 回退到指定版本

## 主要的几个操作
1. git init -> 创建版本库
2. git add 文件名 -> 工作区提交到暂存区
3. git commit -m '注释' -> 暂存区提交到本地仓库

## git remote add origin 仓库地址
1. 把本地仓库与远程仓库关联

## git remote -v
1. 查看本地仓库关联的远程仓库地址

## git push -u origin master
1. git push 本地仓库提交到远程仓库 
2. -u origin master 设置默认远程仓库和分支
3. 执行完命令后，可以直接git push 提交到远程仓库的master 分支
   
## 更新代码
1. 把远程代码更新到本地之前，需要先提交到本地仓库再更新
2. git pull