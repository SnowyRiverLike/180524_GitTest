## 1. 使用git管理项目的基本操作(6个)
    1). 创建本地仓库
       a. 创建.gitignore文件, 指定需要忽略的文件/文件夹
       b. 创建工作区: git init
       c. 创建索引区: git add *
       d. 创建版本区: git commit -m "init"
    2). 创建远程仓库
       a. 登陆github
       b. New Repository
       c. 指定名称
       d. 确定创建
    3). 将本地仓库推送到远程
       a. 关联: git remote add origin https://github.com/zxfjd3g/180524_GitTest.git
       b. 推送: git push origin master
    4). 如果本地有修改, 推送到远程
      a. git add *
      b. git commit -m "update README.md"
      c. git push origin master
    5). 如果远程有修改, 拉取到本地
      a. git pull origin master
