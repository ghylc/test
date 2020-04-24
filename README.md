# Git 常用命令

-   git status：查看代码修改情况；
-   git add .：将暂存区修改内容提交到本地仓库；
-   git add ./src/：将 src 目录下文件添加到暂存区；
-   git commit -am 'descriptions'：基本相当于 git add 和 git commit -m 的组合，但只对跟踪过的文件有效；
-   git commit -m 'descriptions'：将更改和备注存储到新的提交中；
-   git pull：拉取代码到本地；
-   git push：推送代码到远程,格式为 git push origin master:refs/for/master，origin 是远程主机名。第一个 master 是本地分支名，第二个 master 是远程分支名。
-   git push -u：
-   git push --set-upstream origin branch-01：跟原始分支建立跟踪

# 我添加自分支 01
