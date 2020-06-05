# git笔记

## 项目管理

* ( cd )进入项目

* git init 初始化项目

* git status 查看文件编辑状态

* git add 文件名/. 将修改的/新增的文件保存到暂存区

* git commit -m '版本描述'  将暂存区里的文件提交到版本库中

* git log 查看历史版本

* git reflog 查看所有历史版本上一次

### 版本回滚

* git checkout 文件  取消上一次工作区文件的修改

* git reset head 文件 取消上一次暂存区文件的保存回到工作区

* git reset --soft 版本号 回滚至之前某个版本到暂存区

* git reset --mix 版本号  回滚至之前某个版本到工作区修改状态

* git reset --hard 版本号 回滚至之前某个版本到工作区

### 创建分支

* git branch 查看所有分支

* git branch 分支名称  创建分支

* git checkout 分支名称  切换分支

* git gerge 分支名称  合并A分支到B分支要先切换到B分支再合并

输入git log 按住键盘 q 键（英文状态下）即可退出
