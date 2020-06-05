# git笔记

## 项目管理

* ( cd )进入项目

* git init 初始化项目

* git status 查看文件编辑状态

* git add 文件名/. 将修改的/新增的文件保存到暂存区

* git commit -m '版本描述'  将暂存区里的文件提交到版本库中

* git log 查看历史版本

* git reflog 查看所有历史版本

### 版本回滚

* git reset --hard 版本号  回滚至之前某个版本

* git reset head 文件 取消暂存区文件的保存

* git checkout 文件  取消工作区文件的修改
