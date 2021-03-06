ThinkphpHelper 
=============================================

thinkphp代码生成器-2.21	对应Thinkphp版本：5.0.23

![ThinkphpHelper](http://weiyunstudio.qiniudn.com/tph2.jpg)

tph2支持Thinkphp5， TPH支持Thinkphp3.2.2

支持MySQL 和 sqlite数据库，快速构建项目原型，直接生成前后台CRUD代码片段，还可根据需要自行定制代码模板，减少重复劳动。

写这个东西的原因是因为我最近沮丧的发现很多时候我都在做重复的事情，比如重复写最简单的CRUD方法，编写表单，写前台样式表等等。

Thinkphp对于后台操作的支持已经非常强大，再加上最近非常流行的Bootstrap框架让前台样式也变得容易遵循一个标准，于是我决定开始写一个属于自己的代码生成器。

我希望它操作足够简单，能够一看就懂，对MySql和Sqlite数据库都能够稳定生成可复用的CRUD代码就好，还如果还能顺便生成一些符合Bootstrap框架的View代码就更好啦。

ThinkphpHelper诞生至今多谢大家的支持。在这个版本中我放弃了单文件的形式，以便实现更多想法。你可以看到现在界面更漂亮了，功能也更强大了。这个版本最大的亮点就是支持直接生成文件，除了数据库外，你只需要写不超过5行代码就可以快速构建出一个原型系统。我建议你可以根据你的需要自行修改Template文件夹下的模板，使之更符合你的项目需求。

TPH2是针对Thinkphp5开发的版本，原本的TPH继续支持Thinkphp3。在TP5下，只要先配置好你的数据库连接，用把tph2文件夹复制到public（项目公开目录）目录下就可以使用。
TPH2的设计思路是根据数据库信息用模板引擎解析“代码模板”并生成具体文件，所有的代码模板都放在codeRepository目录下，以'_theme'结尾的是代码风格模板目录，其他文件夹则是逻辑代码模板目录，生成时先把逻辑代码模板包含进风格模板再进行渲染，这样的二段渲染方式可以更加灵活的编写合适自己的代码模板仓库。

演示视频:[http://video.weiyunstudio.com/tph.flv](http://video.weiyunstudio.com/tph.flv)
↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓

项目地址：[https://github.com/zhuanqianfish/ThinkphpHelper](https://github.com/zhuanqianfish/ThinkphpHelper)

↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑

ThinkphpHelper遵循Apache2开源协议发布，并提供免费使用。

[支持TPH发展，支付宝或微信捐赠](http://zhuanqianfish.github.io/ThinkphpHelper/donation.html)

=============================================

更新日志：

2.20更新：

增加了项目表单配置，现在可以自定义表单项目类型了，例如checkbox select 日历等等，只要在项目配置里面设置一下即可

============================================

2.10更新：

增加了项目配置功能

增加了一套amaze ui的代码模板

修正路径分隔符的bug

修正代码模板生成时的bug
