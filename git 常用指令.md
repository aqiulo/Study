#Git 基础教程

#### 创建新仓库
	git init

#### 查看仓库状态
	git status

#### 工作流介绍
![](https://i.imgur.com/LpUyzN7.png)

#### 添加（把改动添加到缓存区index）
	git add <filename>
	git add *

#### 提交(把改动提交到HEAD,但还没提交到远端仓库)
	git commit -m "代码提交信息"

#### 推送改动(提交到远程仓库)
	git push origin master