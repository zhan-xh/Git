# git命令复习
## git 命令
1. git init
2. git add
3. .gitignore
4. git commit
5. git status
6. git log
7. git commit -v "xxx"
## 分支开发
1. git branch x
2. git checkout x
3. git merge
4. git branch -d x
## 上传代码到远程仓库
1. 新建Repo
2. 复制ssh地址
3. 命令行输入
    git remote add origin git@github.com:XXX
    git push -u origin master
    //如果是加入分支的话
    git push -u origin x
## 下载远程仓库到本地
1. 下载自己的仓库使用ssh地址更加快捷，下载别人的地址则使用https地址
2. 运行
        git clone git@github.com:XXX
        //上面的地址是要下载的仓库地址
3. cd 此仓库路径
4. 然后就可以在这个仓库进行git add/git commit/git pull/git push

## github搭建博客
利用vscode写.md文件，稍微熟悉markdown语法即可，然后将文件上传到GitHub
## 有疑问的地方
1. 不同的项目上传git-hub是否每次都需要重新新建一个本地仓库？

2. 希望对于具体的版本控制有一个比较清晰的描述教程

3. 对于每一个具体的大部分的学习完成，希望不仅只有视频和书面笔记的书写，更加需要实践的代码演示，以及利用markdown进行博客总结。

