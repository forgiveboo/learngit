1. git init初始化仓库
2. 创建SSH Key
3. git add 文件
4. git commit -m "添加的文件的信息"
5. git remote add origin 仓库远程SSH地址
6. 如果出现atal: remote origin already exists错误 则执行git remote rm origin 再重复上一步
7. git branch -M main
8. git push -u origin main
9. 拉取远程仓库 git pull --rebase origin main
10. 当本地删除了一个或多个文件 
- git rm 文件
- git commit -m "删除的文件的信息"
