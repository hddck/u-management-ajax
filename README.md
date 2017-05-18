# u-management-ajax

主要是一个基于node的express+mongoose+ejs的用户管理系统，实现数据的增删改查。

1、首先你得安装nodejs+mongodb+express(4.X)

2、进入项目路径cd u-management&&npm install,安装所需要的模块

3、进入mongodb的bin目录下启动数据库，cd bin , mongod --dbpath ../u-management/(设置u-management文件夹为我们工程的存储目录并启动数据库，所以你得先建一个u-management文件夹，如果不是在mongodb路径下，记得修改上面的文件夹路径)

4、数据库准备好了，启动项目 npm start，在浏览器输入localhost:3000查看（首页只有一个人员管理是可以点击的，其他的只是为美观，大家无视）

 注意：我的项目并没有注册，而是直接用账号：admin 密码：123456直接登录，有想法的可以自己搞个注册上去，也不费事


