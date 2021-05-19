#SSMDemo使用步骤

1、下载程序到本地

2、用idea打开项目，点击import  maven 导入maven依赖到项目中

3、利用Navicat新建test数据库，导入项目中的test.sql文件

4、安装Tomcat ，在idea上面配置启动文件（配置Tomcat）

5、启动项目，在浏览器中输入localhost:8080,点击链接即可访问（推荐安装postman的Google插件）

6、如需想要部署互联网服务器：参考：https://blog.csdn.net/happy_bigqiang/article/details/82020395
第4，第5点；部署之后；访问http://互联网ip地址:8080/user/index
7、正常会返回json:{"code":100,"msg":"处理成功！","extend":{}} 说明系统正常运行启动了。
