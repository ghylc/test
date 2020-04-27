# Git 常用命令

-   git init：初始化当前目录
-   git clone origin.git local：从远端克隆名为 origin 的仓库到本地 local 文件夹中；
-   git status：查看代码修改情况；
-   git add .：只能提交未跟踪和修改文件，不处理删除文件；
-   git add ./src/：将 src 目录下文件添加到暂存区；
-   git commit -m 'descriptions'：将更改和备注存储到新的提交中；
-   git commit -am 'descriptions'：基本相当于 git add 和 git commit -m 的组合，但只对跟踪过的文件有效；
-   git pull：拉取代码到本地，origin master 为从远程主分支拉取；
-   git push：推送代码到远程,格式为 git push origin master，origin 是远程主机名。第一个 master 是本地分支名，第二个 master 是远程分支名；
-   git push -u：origin master，运行一次后，后面就只需 git push；
-   git push --set-upstream origin branch-01：跟原始分支建立跟踪；
-   git reset --hard HEAD^：重置到上一个版本，HEAD^可换成具体的版本号，版本号用 git log 命令获取；
-   git log --pretty=oneline：查看版本号；
-   git reflog：跟 git log 不同，能显示 git reset 的回退记录；
