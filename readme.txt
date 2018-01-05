Git is a distributed version control system.
Git is free software distributed under the GPL.
git command
    git add <file> # add a file to commit
    git commit -m <"note"> # commit all file to git as a version,-m add a note to this version
    git status # show the workspace status 
    git diff # compare the worspace between workspace of git.
    git log # view the log
    git log --pretty=oneline # show the log with a different view
    git reset  --hard HEAD^ # 回退至上个版本
    git reflog # 显示所有版本号
    git reset --hard <指定版本号> # 回退至指定版本
    git diff HEAD --<fileName> # 查看git中版本与工作区版本的不同
    git checkout -- <fileName> # 丢弃工作区的修改
    git reset HEAD <fileName> # 丢弃工作区的修改(已经add到暂缓区),再执行上句
    git rm <fileName> #将删除的文件提交到暂缓区
    ssh-keygen -t rsa -C "youremail@example.com" # 产生rsa密钥对（默认保存在user/.ssh目录下）
    git remote add origin git@github.com:<username>/<仓库名>.git # 关联github上的仓库
    git push -u origin master # 第一次推送至远程仓库
    git push origin master # 推送至远程仓库
    git clone git@github.com:<用户名>/<仓库名>.git # 从github上clone仓库到本地
    git checkout -b <分支名> # 创建一个分支并切换到这个分支
    git branch <分支名> # 创建一个分支
    git checkout <分支名> # 切换到指定分支
    git branch # 查看所有分支

