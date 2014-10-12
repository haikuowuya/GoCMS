#GoCMS 

基于Go语言和Revel框架的内容管理系统


演示地址：
[http://admin.6574.com.cn/](http://admin.6574.com.cn/)

GoCMS QQ交流群：
[<a target="_blank" href="http://shang.qq.com/wpa/qunwpa?idkey=320f832b05527901497d4ecbf76f54e7634e94dbc146b3dc413cf8f881fbfe5c"><img border="0" src="http://pub.idqqimg.com/wpa/images/group.png" alt="GoCMS交流" title="GoCMS交流"></a>](345304040)

##编译安装说明：

设置GOPATH(安装目录)

	$ export GOPATH=/path/src/admin
	$ cd /path/src/admin

获取源代码，下载完成后会自动编译为GoCMS可执行文件
	
	$ go get github.com/zzdboy/GoCMS
把下载的代码复制到src/admin目录下

修改数据库配置
	
	admin/conf/databases.conf

导入MySQL

	doc目录下gocms.sql

运行
	
	$ nohup revel run admin prod >admin.log &
	设为后台运行

后台地址：

http://localhost:9000

帐号：test, test001
密码：123456

