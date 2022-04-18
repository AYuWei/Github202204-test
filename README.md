# WeChatApplet202204
20220418学习微信小程序借助于Github管理

### 新建分支Master为主分支

1. 该分支只从远程仓库clone来的。
2. 现在创建了一个文件夹Push上去吧。

### 提交不揍。
查看当前状态
1. git status 

将左右的代码打包
1. git add .
2. 
提交到本地仓库
1. git commit -m "填写这次修改的内容备注"

提交到远程仓库
1. git push <remote> <branch>

操作是
```js
git add .
git commit -m "创建了一个文件夹并写明了说明"
git push origin Master
```

## ==============================

创建分支。
1. git branch Develop

切换分支
1. git checkout Develop

创建并切换分支
1. git checkout -b Develop

删除本地分支
1. git checkout -d Develop

查看本地和远程仓库的分支。
1. git branch -a

查看远程分支
1. git branch -r

查看本地分支
1. git branch
   
   
