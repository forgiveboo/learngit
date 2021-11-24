#### 创建本地仓库
   - git init
#### 关联远程仓库
   - 创建SSH Key
   - git add 文件
   - git commit -m "添加的文件的信息"
   - git remote add origin 仓库远程SSH地址
   - git branch -M main
   - git push -u origin main
   - 拉取远程仓库 git pull --rebase origin main
   - 当本地删除了一个或多个文件 
      - git rm 文件
      - git commit -m "删除的文件的信息"
#### 疑难杂症
   - 如果出现atal: remote origin already exists错误 
      - 执行git remote rm origin 再重复上一步
   - git-ssh: connect to host github.com port 22: Connection timed out
      - [解决方法](https://www.jianshu.com/p/c3aac5024877)
