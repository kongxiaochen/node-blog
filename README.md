# node-blog
nodejs+express+mongodb架构
简单的mini blog应用api，结合前端代码：https://github.com/luyanchen/nej-app/

mongodb：对应数据库为blog
启动:node app

#开发环境
<ul>
<li>nodejs v6.9.5</li>
<li>express v4.14.1</li>
<li>mongodb v3.3.0</li>
<li>mongoose v4.8.1</li>
</ul>
api路径/router/index.js

#环境搭建：

####1)express -e blog//创建web
####2)cd blog
####3)npm install express//安装express，
####4)npm install express-generator//安装express命令工具，
####5)npm install//读取根目录中的package.json文件然后安装项目所依赖的包
####6)npm install mongoose//安装mongoose
####7)mongod --dbpath ~/data/MongoDB/db //启动mongodb，注意db路径改为本地db路径
####8)app.js，/router/index.js,/module/db.js分别改为本demo下的文件
####9)node app 启动项目

