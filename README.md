ApiWiki希望通过一个简单的系统，使开发者项目API的文档便于管理和发布，并可以通过评论回复、成为成员再进行修改等，让开发者在API这件事上省心。基于ThinkPHP开发，除开ThinkPHP之外，仅包含入口文件index.php和Application/Apiwiki文件夹。安装之前，先更改Application/Apiwiki/Conf/config.php中的数据库连接，更改index.php中的define AUTH_SALT。然后创建mysql数据库，并将install.sql导入数据库中创建数据表。之后系统即可运行。Apiwiki没有系统后台的概念，没有超级管理员，每一个注册用户都有自己的管理后台，可以创建项目，撰写接口，加入成员等等，请自己注册登陆后去研究。

后面我想做什么？
1. 用户可以对每一个接口、文档进行评论回复、对接口进行补充
2. 项目有用户的权限，执行阅读、修改
3. 根据固定的代码注释，实现自动创建接口字段
