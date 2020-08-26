# Github 初始化仓库

```shell
# 新建文件夹
mkdir 文件夹名称
# 进入文件夹
cd 文件夹名称
# 新建 README.md 文件
touch README.md
# 初始化仓库
git init
# 将 README.md 文件添加至仓库中
git add README.md
# 将仓库中添加的文件进行提交
git commit -m "提交的备注信息"
# 设置远程的仓库地址
git remote add origin 仓库地址
# 将本地提交的内容推送至远程仓库
git push -u origin master
```

