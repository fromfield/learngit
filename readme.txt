廖雪峰：https://www.liaoxuefeng.com/


git：https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000

python：https://www.liaoxuefeng.com/wiki/0014316089557264a6b348958f449949df42a6d3a2e542c000

js：https://www.liaoxuefeng.com/wiki/001434446689867b27157e896e74d51a89c25cc8b43bdb3000




本地代码上传到github流程：
第一步：打开Github网站：https://github.com/，登录自己的账号。
第二步：点击Your profile，进入仓库管理，进入Repositories，点击new创建新项目
第三步：因为GitHub是基于git实现的代码托管，所以git是少不了的。我们要确认电脑上安装了git，没有安装的，就去安装git。至于安装方法，就自行百度吧。
第四步：在本地右击需要传的项目文件夹根目录，点击“Git Bash Here”，打开git命令行。
第五步：按照github新建仓库上的文档提示，提交项目：
1.在命令行中，输入“git init”，使项目文件夹加入git管理；
2.输入“git add .”（不要漏了“.”），将项目文件夹全部内容添加到git。
3.输入“git commit -m "first commit"”（“git commit -m "提交信息"”）
4.输入“git remote add origin https://github.com/fromfield/项目文件.git”（git remote add origin 你自己的https地址），连接你的guthub仓库。
5.输入“git push -u origin master”，上传项目到Github。这里会要求输入Github的账号密码，按要求输入就可以。