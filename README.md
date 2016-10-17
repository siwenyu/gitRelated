# gitRelated

git相关的问题汇总。

使用git在本地创建一个项目的过程
<br>
$ makdir ~/hello-world    //创建一个项目hello-world
<br>
$ cd ~/hello-world       //打开这个项目
<br>
$ git init             //初始化
<br>
$ touch README
<br>
$ git add README        //更新README文件
<br>
$ git commit -m ‘first commit’     //提交更新，并注释信息“first commit”
<br>
$ git remote add origin git@github.com:defnngj/hello-world.git     //连接远程github项目
<br>
$ git push -u origin master     //将本地项目更新到github项目上去
<br>
