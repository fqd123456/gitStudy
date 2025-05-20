我们安装 git 应该安装了一个git bash 终端，可以在这里进行一些操作。这是在linux系统的操作，更正确。

# 切换远程地址
git remote set-url origin 新的地址
git remote -v  查看当前配置的所有远程仓库地址

# 指针提交
git push origin HEAD:fqd-appStyle-v1  将远程最新的提交 提交到远程仓库的xx分支

# 回退
当合并的时候发现有一些问题，可以使用命令进行回退。

git reset --hard HEAD~1 回退到上一次提交的状态
git reset --hard 版本号 回退到指定的版本号。  (git log --online 查看备注 以及版本号。git show 版本号7位缩写形式 查看具体内容)

# 合并
git merge 分支名  合并分支到当前分支。
- 无冲突合并和简单合并。直接merge即可。