# 区块链早起打卡项目趣步模式系统源码

介绍：测试环境： php5.6 mysql5.5请按顺序安装：第一步：修改配置信息修改指引：1：修改数据库连接文件，在 config\database.php这个文件修改里面的数据库连接信息2：修改以上个数据库文件之后把网站源码上传到空间里面————————————————————–第二步：导入数据数据库文件存放：默认放在下载的源码根目录“数据库”文件夹下。一般放了两种类型，一种是SQL语句，一种是MYSQL的物理文件导数据方法一：用phpMyAdmin 导入网站源码根目录的数据库.sql 找到你的数据库！选择你自己的数据库 ，点击导入就好了，导数据方法二：用 Navicat for MySQL等辅助工具 导入网站源码根目录的数据库.sql 找到你的数据库！选择你自己的数据库 ，点击导入就好了，导数据方法三：如果有物理文件，直接拷贝物理文件到你的数据库物理文件地址即可————————————————————– 第三步：设置thinkphp伪静态注：目录需要指向 public————————————————————–第四步：测试到这里网站基本搭建完毕！登录后台试试！后台地址： http://你的域名/admin后台账号密码：用户：admin 密码 3eym.com到此！网站就算搭建好了！后台密码修改：config\hello.php文件注：目录需要指向 public声明：本源码仅供用户编程学习使用，禁止用于商业途径，如果出现任何法务事件与本站无关。————————————————————–程序后台无法登录问题解决办法； 一、若后台密码登录失败，可尝试登录二、后台密码，数据库搜索admin或者user表一般就是，找到登录的用户密码，换成下面的如果遇到MD5加密文件，而又不知道的密码的，请在数据库中换上这组加密的数据吧。后台密码替换:16位7a57a5a743894a0e 后台密码替换:32位21232f297a57a5a743894a0e4a801fc3 后台密码就是:admin三、在前台注册一个普通用户然后到数据库把这个用户的密码，覆盖管理员的密码一般就可以了。有salt的话，salt也要替换四、再不行，就直接修改程序，任何密码都让登录，登录后修改密码保存，再把程序改回来。




<p style="color: red;">源代码下载地址：<a href="https://mega-file.org/93eCp" style="color: red;">https://mega-file.org/93eCp</a></p>