**1. 使用ssh-keygen -t rsa -C "youremail@example.com"命令生成SSH秘钥**
**2. 登录github在设置中添加id_rsa.pub（id_rsa.pub位于/home/.ssh文件夹）内容**
**3. 使用git remote add origin git@server-name:path/repo-name.git 关联远程仓库**
**4. 第一次提交使用 git push -u origin master
接下来的提交都使用 git push origin master**