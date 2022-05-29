#Git笔记

工作区->暂存区->Git远端

1.工作区添加入暂存区：
git add filepath

2.暂存区提交到分支：
git commit -m "提交日志"

3.本地分支提交到远端
git push

4.重置：
1. 重置到上一个版本：
git reset --hard HEAD^
2. 撤销commit但不撤销add
git reset --soft HEAD^
3. 撤销commit且撤销add
git reset --mixed HEAD^
4. 还未add撤销修改 会丢失修改
git restore filepath
5. 已经add撤销add操作 不会丢失修改
git restore --stage filepath
