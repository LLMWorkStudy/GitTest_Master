# GitTest_Master

## 必须是公开的仓库
## https://github.com/LLMWorkStudy/GitTest_Master.git -> https://${username}:${usercode}@github.com/LLMWorkStudy/GitTest_Master.git
###
<!-- [user]
	name = ${username}
	password = ${usercode} -->
###

# clone
## git clone --recurse-submodules <repository_url>
### git submodule status：查看子模块状态。使用该命令可以查看当前 Git 仓库中包含的子模块的状态。
### git submodule foreach：对子模块执行命令。使用该命令可以对当前 Git 仓库中包含的所有子模块执行指定的命令

# 添加
### git submodule add <submodule_url> 目录名称

# 默认是当前子模块
### git submodule init [子模块] 
### git submodule update [子模块]

# 移除
## git submodule deinit -force
### git rm <submodule>

