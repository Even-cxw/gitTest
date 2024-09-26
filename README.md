# git-笔记

- 使用vscode插件 `git Graph`

## 常用分支
1. release 发布分支：用于发布版本，一般从 develop 分支上拉取，合并完成后，再合并到 master 分支，然后打上标签，并发布到生产环境。
2. feature 功能分支,。团队成员中每个人都维护一个自己的feature分支。
3. fixbug 分支：用于修复bug。 
4. develop 开发分支：用于开发新功能。
5. master 主分支：用于发布正式版本。

## 常用命令
1. 创建并且切换分支命令： `git checkout -b <分支名>`
2. 推送分支到远程仓库命令：`git push origin <分支名>`
3. 拉取远程分支到本地命令：`git pull origin <分支名>`
4. 合并分支命令：`git merge <分支名>`
5. 删除分支命令：`git branch -d <分支名>`


