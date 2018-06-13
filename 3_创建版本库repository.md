**创建版本库**
*1.创建空目录*
mkdir learngit
cd learngit
pwd

*2.将目录初始化成Git仓库*
git init

*3.将文件添加到版本库*
touch example.md
然后编辑example.md
(建议添加的文件使用utf8编码)

*4.把文件添加到Git仓库*
git add example.md

*5.把文件提交到Git仓库*
git commit -m "this is the introduction of the commit"
(-m后是本次提交的说明)
可以在进行多次add后使用一次commit命令提交


