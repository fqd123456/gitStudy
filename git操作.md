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
<<<<<<< HEAD



## 分支提交 合并
1. git checkout 分支名  切换分支  
    加 -b 可以创建一个新的分支。
- 如果在当前分支修改，push到老分支，会提示都是新的。因为你并没有在老分支commit

2. git merge 分支名 合并分支到当前分支。

=======
- 无冲突合并和简单合并。直接merge即可。
>>>>>>> fqd2
