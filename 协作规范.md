## Github协作规范
***
使用Github的organization进行协作开发。

### 创建组织
***
* 基本流程：create organization -> invite members -> join the organization；
* 将仓库权限设置组织成员可写。

### 协作
***
* 为仓库创建dev分支

* 组织成员clone仓库到本地仓库，在本地仓库的dev分支进行开发

* 成员每次提交代码前，需要从远程仓库拉取dev分支更新本地仓库dev分支，减少或避免冲突

* 更新dev分支后，再将本地dev分支的修改commit并push到远程仓库dev分支

* 确认功能完善且代码无误后，再合并dev分支到master分支


