# gitlearn

**获取ssh**
 ssh-keygen -t rsa -C “wangtao@bamaying.com”

1. git init

    将一个目录初始化为 Git 仓库

2. git clone

    复制一个仓库

3. git add

    添加文件到缓存

4. git status

    查看你的文件在工作目录与缓存的状态

5. git diff

    显示已写入缓存与已修改但尚未写入缓存的改动的区别

   git diff --cached  查看已缓存的改动

   git diff HEAD  查看已缓存的与未缓存的所有改动

   git diff --stat 显示摘要而非整个diff

6. git commit

    记录缓存内容的快照

    git commit -a  自动将在提交前将已记录、修改的文件放入缓存区

7. git reset HEAD --file

    取消缓存已缓存的内容

8. git rm file

    将文件从缓存区移除

    如果要在工作目录中保留 git rm --cached

9. git branch

    列出，创建与管理工作上下文   列出可用的分支

    git branch (name)      创建新分支

    git branch -d (name)   删除分支


10. git checkout -b (name)

    创建新分支，并立即切换到

11. git merge (name)

    将name分支合并到当前分支

12. git log

    显示一个分支中提交的更改记录

13. git tag -a ( 标签 )

    给历史记录中一个重要一点标签

14. git remote

    列出远端别名

    git remote -v  列出远端与链接地址

    git remote add 地址    为你的项目添加一个新的远端仓库

    git remote rm [alias] 删除现存的某个别名

15. git fetch github

    从远端仓库下载新分支与数据

16. git pull

    从远端仓库提取数据并尝试合并到当前分支

17. git push

    推送你的新分支与数据到某个远端仓库
































