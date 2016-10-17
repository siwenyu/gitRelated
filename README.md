# gitRelated

git相关的问题汇总。

使用git在本地创建一个项目的过程
$ makdir ~/hello-world    //创建一个项目hello-world
$ cd ~/hello-world       //打开这个项目
$ git init             //初始化
$ touch README
$ git add README        //更新README文件
$ git commit -m ‘first commit’     //提交更新，并注释信息“first commit”
$ git remote add origin git@github.com:defnngj/hello-world.git     //连接远程github项目
$ git push -u origin master     //将本地项目更新到github项目上去
