# 生产规范与指南

## 1. Github协作

### 1.1 Github组织

使用团队公用Github账号创建organization，邀请所有团队成员加入组织，设置权限为write。

### 1.2 Git代码提交规范

* 仓库分支

	-master<br/>
	-dev

* 代码更新修改

	+ 组织成员clone仓库到本地仓库，在本地仓库的dev分支进行开发。

	+ 成员每次提交代码前，需要从远程仓库拉取dev分支更新本地仓库dev分支，减少或避免冲突。

	+ 更新dev分支后，再将本地dev分支的修改commit并push到远程仓库dev分支。

	+ 确认功能完善且代码无误后，再合并dev分支到master分支。

### 2. Kanban使用

使用organization下的Projects创建Bronze-Tiki项目，设置模板为Kanban-Automated。

* 成员根据每次会议讨论结果，为自己设定几个任务，添加至Kanban中的To do列。

* Kanban任务开始时，将任务card移动至In progress列。

* Kanban任务完成时，将任务card移动至Done列。

* Kanban任务每周更新一次。

### 3. 代码规范

* 前端代码规范参考：[前端代码规范及最佳实践|ISOBAR](https://coderlmn.github.io/code-standards/)

（待完善）