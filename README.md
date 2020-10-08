# tutorial of git
## Git and github
#### 初始化本地仓库
- git init：初始化当前目录为git 本地仓库
- git add README.md：推送README.md文件当暂存区(可撤销，也可提交到本地仓库)
- git commit -m "注释信息"：提交当前暂存区的内容到本地仓库，并附带注释"注释信息"

#### 推送分支到远程仓库
- git remote add [short_name] [url]：添加远程仓库，例如git remote add notes_git git@github.com:ShiyinTan/notes_of_git.git
- git push origin master：将本地的master分支提交到远程仓库origin，例如git push notes_git master

#### 提取远程仓库的更新
- git fetch origin master：从远程仓库origin上下载名为master的分支到本地分支origin/master中，例如git fetch notes_git
- git merge origin/master：合并origin/master分支到当前所在分支，因此与远程仓库无关。
