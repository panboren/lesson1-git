git步骤：
1 创建目录
2 touch README.md
3 git init
4 写好项目目录文件
5 git status 查看文件是否齐全
6 创建一个.gitignore文件，把不要上传的文件放里面。 (.idea node_modnles .DS_Store)
7 git不上传空文件夹，放.gitkeep文件保留。
8 git status 检查状态是否完整
9 git add .
10 git commit -m "message"
11 到github上创建仓库（创建仓库会有提示）
12 git remote add origin 地址
13 git remote -v 查看提交信息
14 git remote rm b 如果错了删除关联
15 git push origin master (输入账号密码)
16 新增文件 （拉取代码 git pull origin master）
17 写好新增的文件（esc=>：wq 保存）
18 git push origin master
19 线上线下都改会冲突
   git pull origin master =>把不要的内容删掉，=>git add .
   =>git commit -m "massage"=>git push origin master