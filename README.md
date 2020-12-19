# gitdemo
IDEA的git使用样例
第一次尝试使用IDEA上传自己的git项目

git命令（常用的）：
git init本地初始化新的git项目
git add . 新增文件添加到暂存区
touch README新建文件（和linux一样）
git add README 添加文件
git commit -m 'first commit' 提交本地库 -m为参数（message） 后面加commit概括内容
git pull 本地与服务器端同步
git branch 查看本地所有分支
git status 查看当前状态 
git checkout -b dev 建立一个新的本地分支dev
git merge origin/dev 将分支dev与当前分支进行合并
git commit -a 提交当前repos的所有的改变
git add [file name] 添加一个文件到git index
git commit -v 当你用－v参数的时候可以看commit的差异
