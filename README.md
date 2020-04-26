# Git 常用命令

-   git status：查看代码修改情况；
-   git add .：将暂存区修改内容提交到本地仓库；
-   git add ./src/：将 src 目录下文件添加到暂存区；
-   git commit -am 'descriptions'：基本相当于 git add 和 git commit -m 的组合，但只对跟踪过的文件有效；
-   git commit -m 'descriptions'：将更改和备注存储到新的提交中；
-   git pull：拉取代码到本地，origin master 为从远程主分支拉取；
-   git push：推送代码到远程,格式为 git push origin master，origin 是远程主机名。第一个 master 是本地分支名，第二个 master 是远程分支名；
-   git push -u：origin master，运行一次后，后面就只需 git push；
-   git push --set-upstream origin branch-01：跟原始分支建立跟踪；
-   git reset --hard HEAD^：重置到上一个版本，HEAD^可换成具体的版本号，版本号用 git log 命令获取；
-   git log --pretty=oneline：查看版本号；
-   测试 git push
-   added in branch-03
-
