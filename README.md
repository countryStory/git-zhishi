# git-zhishi
## git知识总结
### 1.代码提交常用  

  git add .                                     --保存工作区所有改动文件到暂存区   

  git commit -m ""                              --保存暂存区到本地仓库    

  git pull origin daily/0.0.1                   --从远程仓库拉取代码到工作区   

  git push origin daily/0.0.1                   --把本地仓库代码提交到远程仓库     
     
  ----------   
### 2.常用命令    

     git branch daily/0.0.1 （创建分之）
     git checkout daily/0.0.1 （切换分之）
     git checkout -b daily/0.0.1 （创建并切换分之）
     
  ----------    
  
### 分之
git merge daily/0.0.1 （合并到当前分之）    

git branch -D daily/0.0.1 （删除本地分之）    

git push origin :daily/0.0.1 （删除远程分支）

### tag     
git tag （列出所有tag）    

git tag -d v1  （删除本地tag）    

git push origin :v1 （删除远程tag）   

### 查看信息   
git log （显示当前分支的版本信息）   

git status （显示变更文件）   

git reflog （显示所有的本地提交，包括所有分之和撤销的commit）

### 撤销    
git reset --hard HEAD~1 （丢弃最近一次提交）    

git reset --hard esajdsaj9384  （回滚到当前提交）
