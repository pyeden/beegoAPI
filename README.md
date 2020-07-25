# 这是一个go语言的后端api框架

## Beego

## 创建项目
```bash
bee api beegoAPI
```

## 启动项目
```bash
bee run -gendoc=true -downdoc=true

```

## 项目地址


http://127.0.0.1:5000/


## 项目文档地址

http://127.0.0.1:5000/swagger/

## 分支管理
```bash
# 初始化项目仓库
git init

# 添加项目文件
git add .

# 本地提交
git commit -m "first commit"

# 关联远端服务器仓库
git remote add origin git@github.com:FutureSenzhong/beegoAPI.git

# 提交文件跟踪远程仓库
git push -u origin master

# 本地创建并切换到一个开发分支
git checkout -b dev_sz

# 提交开发分支跟踪远程仓库开发分支
git push -u origin dev_sz

# 查看分支
git branch -a

# 分支如下:
* dev_sz
  master
  remotes/origin/dev_sz
  remotes/origin/master

# 查看本地分支远程分支跟踪状态
git branch -vv

# 分支跟踪状态如下:
* dev_sz f9f9e76 [origin/dev_sz] project init
  master f9f9e76 [origin/master] project init


```
ps：现在本地和远端都有两个分支了，一般在本地dev分支开发，完成后push到远程dev分支，review code之后可以创建pull request请求把dev分支合并到master主分支
