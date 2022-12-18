# Git 的使用

## 概念

branch 分支

## 常用命令

```shell
git clone https://github.com/ohmyzsh/ohmyzsh.git  # 下载别人的仓库代码到当前目录
git init  # 初始化仓库
git branch # 查看当前分支名
git branch -m ${string} # 修改当前分支名字

git checkout ${string} # 切换到另一个分支
git checkout -b ${string} # 创建一个新的分支
git status # 查看当前仓库的变更情况
git add ${file} # 添加修改
git commit -m ${string} # 给当前修改添加备注信息
git push origin main # 把当前本地仓库所有的修改推上云端
git pull # 把云端新的修改拉下来

git merge ${branch} # 把branch分支合并到当前分支

git log # 查看当前操作日志

```

