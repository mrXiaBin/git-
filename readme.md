## 把代码存储到.git仓储中
1.把代码存储到 .git 仓储中
  + `git add ./ readme.me`
  + `git add ./` 把所有的修改的文件添加到大门口
  
2.把仓储门口的额代码放到里面的房间中去
  + `git commit -m` "1111"
 
## 可以一次性把我们修改的代码放到.git仓储中
  + `git commit --all -m`

3. 查看仓库状态码
  + `git status`

## git 中的忽略文件
- .gitignore,这个文件中可以设置要被忽略的文件或者目录。

## 查看日志 
- `git log` 查看历史提交的日志
- `git log --oneline` 可以看到简洁版的日志 

##  回退到指定的版本
- `git reset --hard Head~0`
  + 表示回退到上一次代码提交时的状态
- `git reset --hard Head~1`
  + 表示回退到上上次代码提交时的状态

- `git reset --hard [版本号]`
  + 可以通过版本号来
- `git reflog`