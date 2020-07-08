
### Git 常用命令
[更多Git命令参考](https://gitee.com/all-about-git)
* git 普通操作
1. `git init` : 初始化仓库 
2. `git add xxx`: 添加文件到暂存区
3. `git commit -m "提交的信息msg"` : 将暂存区文件提交到本地仓库
4. `git remote add origin [url]` : 本地仓库与远程仓库关联
5. `git push origin master` : 本地push 到远程, 之后输入github 用户名和密码

*  git 其他操作
6. `git status` : 查看所有文件状态
7. `git status [filename]` : 查看指定文件状态
8. `git add .` : 添加所有文件到暂存区
9. `git clone [url]` : clone 远程项目到本地
10. `git pull origin master` : 拉取远程到本地
11. `git rm --cached -r [useless]` : 删除远程无用的文件，保留本地, 如`git rm --cached -r .idea`
12. `git push --set-upstream origin master` :只关联一个远程时，设置这个之后，可以使用`git push` 

* git 分支操作
13. `git branch` : 列出所有本地分支
13. `git branch -r` : 列出所有远程分支
14. `git branch [branch-name]` : 新建一个分支，但是依旧停留在当前分支
15. `git checkout -b [branch-name]`: 新建一个分支，并切换到该分支
15. `git checkout [branch-name]`: 切换到指定分支
16. `git merge [branch]`: 合并指定分支到当前分支
17. `git branch -d [branch-name]`：删除分支
18. `git push origin -delete [branch-name]`:删除远程分支
19. `git branch -dr [remote/branch-name]`:删除远程分支
