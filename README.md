# weiyi32
SSM图书借阅管理信息系统的 设计与实现

#### 介绍
图书借阅管理信息系统采用Spring MVC当做框架，Eclipse作为开发环境，实现则采用Java语言，MySQL作为系统管理的数据库。这样就可以保证数据的时效性，做到定期更新。此系统分为两大部分：普通用户和管理员。普通用户具备的功能如下：查看图书信息、添加心愿书单、续借图书等。管理员所具备的功能如下：还书处理、借书处理、增加用户、修改图书信息、新书入库等。

本系统主要是为了方便用户使用且方便管理员管理后台数据。用户通过该系统可以搜索书籍、添加书单和借阅图书。管理员可以添加图书、查询图书、编辑图书信息和管理用户的信息。通过需求分析，本系统主要包括以下功能模块
![输入图片说明](https://images.gitee.com/uploads/images/2020/1128/014834_c6838b2e_4865385.png "屏幕截图.png")

（1）用户登录模块
   用户想要借阅图书之前必须登陆自己的用户名和密码，当看到“**，您好，欢迎来到电子图书馆！”字样说明登陆成功。
（2）用户查询图书模块
用户登录后可以浏览所有图书，并且可以查看图书的详细信息，也可以通过在搜索框搜索图书名来查找图书。
（3）用户添加心愿书单模块 
有自己感兴趣的图书就可以添加到心愿书单，心愿书单里可以看到图书的唯一编码，还可以进行预约或者删除。
（4）用户借阅模块 
借阅图书后可以看到图书名称、借阅日期、剩余借阅天数，如果不能及时还书可以点击“续借”按钮。
（5）后台用户管理模块 
首先，只有图书管理员凭借自己的用户名和密码才能后台管理界面。点击“用户管理”按钮，可以对用户进行搜索、删除。点击“用户增加”按钮，可以对新用户进行操作，输入借阅证号、姓名以及密码即可添加新用户。
（6）后台图书管理模块 
当需要更改图书的名称、摆放位置或者价格时，可以点击“编辑图书”按钮。点击“查询图书”按钮，输入唯一图书编码可以查到关于这本书的作者、位置、价格等。当有新书入库时，点击“添加图书”按钮，首先点击“选择文件”加入图书的封面，然后输入图书的条形码、唯一编码、图书名称、作者等信息即可做到新书入库。

![输入图片说明](https://images.gitee.com/uploads/images/2020/1128/014857_eece7536_4865385.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1128/014905_a341cf61_4865385.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1128/014912_7863289d_4865385.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1128/014919_ce376bb5_4865385.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1128/014926_afb35004_4865385.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1128/014932_d41994b7_4865385.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1128/014939_40068ddd_4865385.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1128/014945_6acafddf_4865385.png "屏幕截图.png")

工作室长期接单 招校园实力代理
需要源码请加我一下联系方式
联系Q：2762501186
![输入图片说明](https://images.gitee.com/uploads/images/2020/1119/003728_cd598bb9_4865385.jpeg "微信.jpg")
