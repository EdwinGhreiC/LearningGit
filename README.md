# LearningGit
Git教程 - by Greecer

1. 初始化：git init
2. 当前状态：git status
3. 添加到缓存区：git add filename
4. 添加多个文件：git add filename1 filename2 ...
5. 查看不同：git diff filename
6. 提交：git commit -m "xxx"
7. 查看日志：git log
8. 倒回某一个版本（先用git log找到那个版本的SHA）：git reset SHA的前7位
9. 检查最近提交：git show HEAD
10. 恢复到最近一次提交：git checkout HEAD filename
11. 撤销缓冲区内的尚未commit的add：git reset HEAD filename
12. 创建新分支：git branch 新分支名称
13. 切换到新分支：git checkout 分支名称
14. 当前分支和另一分支合并：git merge 分支名称
15. 解决冲突：手工修正后，重新git add，再git commit
16. 删除分支：git branch -d 分支名称
17. 克隆：git clone 远程地址 本地文件夹
18. 列出远程项目：git remote -v
19. 取得远程的最新更新：git fetch
20. 取得后再合并：git merge origin/master
21. 多人协作流程：git fetch  ->  git merge 合并到主分支 -> 新建分支 -> 提交分支到远端 -> 管理员负责合并到主分支
22. push到github：git remote add origin git@github.com:用户名/learngit.git
23. 第一次推送：关联后，使用命令git push -u origin master第一次推送master分支的所有内容
24. 推送后的修改：此后，每次本地提交后，只要有必要，就可以使用命令git push origin master推送最新修改
