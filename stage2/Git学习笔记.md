# ❤️我的Git学习笔记

##  🤔Git是什么
Git是目前世界上最先进的分布式版本控制系统（没有之一）
不但能自动记录每次文件的改动，还可以让同事协作编辑
是分布式的版本控制系统：有一个中央服务器负责方便用户交换修改的内容

## 🔗资源教程
1. [廖雪峰](https://liaoxuefeng.com/books/git/create-repo/index.html)
2. [git官方教程](https://git-scm.com/book/zh/v2/Git-%E5%9F%BA%E7%A1%80-%E8%8E%B7%E5%8F%96-Git-%E4%BB%93%E5%BA%93)
3. [抖音博主木铎](https://www.douyin.com/user/MS4wLjABAAAAwV7vTHkvSkTpDpJJ_3U_z0AEYoBvdkjRR9N46moTgFz9quenLnYUA10MVth51wiN?modal_id=7704584379753975066)

## ⌛Git Bash使用流程
clone-add-commit-push-pull
1. clone：克隆。只需一次，在Git Bash输入`git clone <仓库地址>`，即可把GitHub里的仓库内所有文档+记录下载一份到了本地电脑里；
2. add：暂存。输入`git add 文件地址`将文件暂存等待提交，可以add多个文件一次提交上传（`git add .`是放当前文件夹里所有改动）；
3. commit：提交、存档。输入`git commit -m"编辑说明"`将暂存里的文件一次性存起来；
4. push：推送。输入`git push`将存档里的文件推送至GitHub的仓库，同步更改；
5. pull：拉取更新：输入`git push`拉取最新的记录，同步最近记录。

&emsp;&emsp;git bash的使用需要自己输入代码并且常用的快捷键在这里并没有效果，因此不够直观还是稍微有一点麻烦，我认为用VS Code比较方便。因为VS Code以图像化模块化的界面展示操作，更通用更直观更符合我们的新手操作习惯
