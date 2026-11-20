# ❤️我的Git学习感想
>—— 张颢宸

## 学习背景
&emsp;&emsp;由网页端的操作深化转至专门的版本控制系统里操作，以此开始学习git的基础操作；将心得感想上传至新思路的文件夹，以此学习如何与他人协作完成项目。

## 学习目录
- 这是[A 关于Git](#a-关于Git)
- 这是[B 关于协作](#b-关于协作)

## 学习内容
### A 关于Git
1. Git Bash的使用：我在学习笔记中做了一定的阐述，此处不过多赘述，重点讲我在使用时的额外发现
2. 额外发现：因为我比较喜欢使用快捷键，然后发现以前常用的快捷键（ctrl+z/x/c/v）都不管用了，于是一查发现：

| 快捷键 | 功能 |
|------|------|
| ctrl+shift+c/ctrl+insert | 复制 |
| ctrl+shift+s/shfit+insert | 粘贴 |
| ctrl+a | 跳转至行首 |
| ctrl+c | 跳转至行尾 |
-  cd：改变目录
-  cd ..：退回上一层
-  ls：陈列文件
-  pwd：查看当前所处目录
-  ......
### B 关于协作
协作比正常上传文件到GitHub多了几步：
1. 我们需要先Fork一份别人的仓库
2. 同样的clone到本地，然后cd进入该仓库
3. 协作不允许直接在main上改所以要通过`git checkout -b 分支名`来新建一条分支
4. 添加文件，然后add-commit-push，但commit时必须写清提交说明
5. 返回Fork的库提起PR

## 参考资料
1. [我的Git学习笔记](https://github.com/sujiujiang/Tasks/blob/main/stage2/Git%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0.md)
2. [Git Bash的常用快捷键及命令](https://blog.csdn.net/m0_51371693/article/details/122626153)
3. [GitHub那些必会的操作](https://www.douyin.com/user/MS4wLjABAAAAXqPwcFXVI8_5uKKmV4H_f-iVgCZ7zkryDqgMjb35SZ3gHMtrTZpE6_8Sphw-OzI8?from_tab_name=main&modal_id=7606539705190333681)
4. [提交说明规范](https://www.conventionalcommits.org/en/v1.0.0/)
