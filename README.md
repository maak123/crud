crud
====

CRUD is Really Urgly coDed -- 课设毕设快速原型

表设计原则

1、每个表必须有id，自增类型

2、每个表id后的第一个字符型字段被当做外键关联的显示值

3、外键一律以表名_id进行命名。

datadic表用于翻译英文表名列名到中文,建表语句在db.sql。

符合上述原则设计表，自动实现菜单、各表增删改，用于快速建立小型系统原型。

暂不支持超文本编辑、文件上传。

数据库配置文件在WEB-INF/db.prop

![image](https://github.com/zhblue/crud/blob/master/crud/crud.png)




