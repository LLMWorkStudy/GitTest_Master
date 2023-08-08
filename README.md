# GitTest_Master

## 必须是公开的仓库
## https://github.com/LLMWorkStudy/GitTest_Master.git -> https://${username}:${usercode}@github.com/LLMWorkStudy/GitTest_Master.git
###
<!-- [user]
	name = ${username}
	password = ${usercode} -->
###

# clone
git clone --recurse-submodules <repository_url>
git submodule status：查看子模块状态。使用该命令可以查看当前 Git 仓库中包含的子模块的状态。
git submodule foreach：对子模块执行命令。使用该命令可以对当前 Git 仓库中包含的所有子模块执行指定的命令

# 添加
git submodule add <submodule_url> 目录名称

# 默认是当前子模块
git submodule init [子模块] 
git submodule update [子模块]

# 移除
git submodule deinit -force
git rm <submodule>


###
# git push
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
https://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@github.com/LLMWorkStudy/GitTest_Master.git
# 有两种方式。
之后用自己生成的token登录，把上面生成的token粘贴到输入密码的位置。
如果 push 等操作没有出现输入密码选项，请先输入如下命令，之后就可以看到输入密码选项了。
# git config --system --unset credential.helper

把token直接添加远程仓库链接中，这样就可以避免同一个仓库每次提交代码都要输入token了：
# git remote set-url origin https://<your_token>@github.com/<USERNAME>/<REPO>.git
<your_token>：换成你自己得到的token
<USERNAME>：是你自己github的用户名
<REPO>：是你的仓库名称

