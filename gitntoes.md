#Git笔记

1.工作区添加入暂存区：
git add readme.txt

2.暂存区提交到分支：
git commit -m "提交日志"

3.本地分支提交到远端
git push

4.重置：
1. 重置到上一个版本：
git reset --hard HEAD^
2. 撤销commit但不撤销add
git reset --soft HEAD^
3. 撤销add
git reset --mixde HEAD^



