![河北师范大学软件学院](./image/logo.png)

# Hibernate框架开发

Hibernate是一个开放源代码的对象关系映射框架，它对JDBC进行了非常轻量级的对象封装，使得Java程序员可以随心所欲的使用对象编程思维来操纵数据库。 Hibernate可以应用在任何使用JDBC的场合，既可以在Java的客户端程序使用，也可以在Servlet/JSP的Web应用中使用，最具革命意义的是，Hibernate可以在应用EJB的J2EE架构中取代CMP，完成数据持久化的重任。

## 课程目标

通过本课程的学习，要求学生达到下列基本目标：

1. 熟练的运用Hibernate框架进行企业应用的开发； 
2. 深入了解Hibernate框架中的ORM概念；
3. 掌握Hibernate框架的理论基础；
4. 掌握Hibernate框架和其他框架的整合技术及开发。

## 课程资料

|资料|链接|
|:---:|:---|
|教学大纲|[<img src="./image/presentation.png" height="15" />查看](./meterials/outline.pdf)  [<img src="./image/download.png" height="15" />下载](./meterials/outline.doc) |
|进度计划|[<img src="./image/presentation.png" height="15" />查看](./meterials/schedule.pdf)  [<img src="./image/download.png" height="15" />下载](./meterials/schedule.doc) |
|备课记录|[<img src="./image/presentation.png" height="15" />查看](./preparelog) |

## 课程内容

| 章节 | 名称 | 内容 | 课件 | 课堂Demo | 
|:---:|:---|:---|:---|:---|
|第一章|Hibernate框架的搭建 |- 分层体系结构与持久化<br/>- 软件的模型及ORM<br/>- Hibernate介绍<br/>- 第一个Hibernate程序|[<img src="./image/presentation.png" height="15" />查看](./ch01-hibernate-architecture/ch01-hibernate-architecture.pdf) <br/>[<img src="./image/download.png" height="15" />下载](./meterials/slides/ch01-hibernate-architecture.pptx)|1.JDBC进行持久化[<img src="./image/download.png" height="15" />下载](./ch01-hibernate-architecture/ch01-demo-01.7z)<br/>2.Hibernate进行持久化[<img src="./image/download.png" height="15" />下载](./ch01-hibernate-architecture/ch01-demo-02.7z)|
|第二章|Hibernate单实体映射 |- 单实体映射基础<br/>- 单实体的属性映射<br/>- 单实体的对象标识符映射<br/>- 使用注解映射单实体|[<img src="./image/presentation.png" height="15" />查看](./ch02-single-entity-mapping/ch02-single-entity-mapping.pdf) <br/>[<img src="./image/download.png" height="15" />下载](./meterials/slides/ch02-single-entity-mapping.pptx)|1.单实体映射[<img src="./image/download.png" height="15" />下载](./ch02-single-entity-mapping/ch02-demo-01.7z)<br/>2.单实体属性映射[<img src="./image/download.png" height="15" />下载](./ch02-single-entity-mapping/ch02-demo-02.7z)<br/>3.单实体对象标识符映射[<img src="./image/download.png" height="15" />下载](./ch02-single-entity-mapping/ch02-demo-03.7z)<br/>4.使用注解方式实现单实体映射[<img src="./image/download.png" height="15" />下载](./ch02-single-entity-mapping/ch02-demo-04.7z)|
|第三章|Hibernate继承关系映射 |- 每个具体类对应一张表<br>- 每个类层次对应一张表<br/>- 每个类对应一张表<br>- 三种映射方式对比|[<img src="./image/presentation.png" height="15" />查看](./ch03-inheritance-mapping/ch03-inheritance-mapping.pdf) <br/>[<img src="./image/download.png" height="15" />下载](./meterials/slides/ch03-inheritance-mapping.pptx)|1.继承映射-每个具体类对应一个表[<img src="./image/download.png" height="15" />下载](./ch03-inheritance-mapping/ch03-demo-01.7z)<br/>2.继承映射-每个父类对应一个表[<img src="./image/download.png" height="15" />下载](./ch03-inheritance-mapping/ch03-demo-02.7z)<br/>3.继承映射-每个类对应一个表[<img src="./image/download.png" height="15" />下载](./ch03-inheritance-mapping/ch03-demo-03.7z)<br/>4.注解方式实现继承映射-每个具体类对应一个表[<img src="./image/download.png" height="15" />下载](./ch03-inheritance-mapping/ch03-demo-04.7z)<br/>5.注解方式实现继承映射-每个父类对应一个表[<img src="./image/download.png" height="15" />下载](./ch03-inheritance-mapping/ch03-demo-05.7z)<br/>6.注解方式实现继承映射-每个类对应一个表[<img src="./image/download.png" height="15" />下载](./ch03-inheritance-mapping/ch03-demo-06.7z)|
|第四章|Hibernate一对一关联映射 |- 一对一关联映射<br/>- 组合关系映射|[<img src="./image/presentation.png" height="15" />查看](./ch04-one-to-one-mapping/ch04-one-to-one-mapping.pdf) <br/>[<img src="./image/download.png" height="15" />下载](./meterials/slides/ch04-one-to-one-mapping.pptx)|1.一对一关联映射-主键关联方式[<img src="./image/download.png" height="15" />下载](./ch04-one-to-one-mapping/ch04-demo-01.7z)<br/>2.一对一关联映射-唯一外键关联方式[<img src="./image/download.png" height="15" />下载](./ch04-one-to-one-mapping/ch04-demo-02.7z)<br/>3.组合关系映射[<img src="./image/download.png" height="15" />下载](./ch04-one-to-one-mapping/ch04-demo-03.7z)<br/>4.注解方式实现一对一关联映射-主键关联方式[<img src="./image/download.png" height="15" />下载](./ch04-one-to-one-mapping/ch04-demo-04.7z)<br/>5.注解方式实现一对一关联映射-唯一外键关联方式[<img src="./image/download.png" height="15" />下载](./ch04-one-to-one-mapping/ch04-demo-05.7z)<br/>6.注解方式实现组合关系映射[<img src="./image/download.png" height="15" />下载](./ch04-one-to-one-mapping/ch04-demo-06.7z)|
|第五章|Hibernate一对多关联映射 |- 实体一对多关联<br/>- 数据库一对多关联<br/>- Hibernate 单向一对多关联<br/>- Hibernate 双向一对多关联|[<img src="./image/presentation.png" height="15" />查看](./ch05-one-to-many-mapping/ch05-one-to-many-mapping.pdf) <br/>[<img src="./image/download.png" height="15" />下载](./meterials/slides/ch05-one-to-many-mapping.pptx)|1.单向一对多关联映射（Set）[<img src="./image/download.png" height="15" />下载](./ch05-one-to-many-mapping/ch05-demo-01.7z)<br/>2.单向一对多关联映射（List）[<img src="./image/download.png" height="15" />下载](./ch05-one-to-many-mapping/ch05-demo-02.7z)<br/>3.单向一对多关联映射（Map）[<img src="./image/download.png" height="15" />下载](./ch05-one-to-many-mapping/ch05-demo-03.7z)<br/>4.双向一对多关联映射[<img src="./image/download.png" height="15" />下载](./ch05-one-to-many-mapping/ch05-demo-04.7z)<br/>5.注解方式实现双向一对多关联映射[<img src="./image/download.png" height="15" />下载](./ch05-one-to-many-mapping/ch05-demo-05.7z)|
|第六章|Hibernate多对多关联映射 |- 实体多对多关联<br/>- 数据库多对多关联<br/>- Hibernate多对多关联映射|[<img src="./image/presentation.png" height="15" />查看](./ch06-many-to-many-mapping/ch06-many-to-many-mapping.pdf) <br/>[<img src="./image/download.png" height="15" />下载](./meterials/slides/ch06-many-to-many-mapping.pptx)|1.多对多关联映射[<img src="./image/download.png" height="15" />下载](./ch06-many-to-many-mapping/ch06-demo-01.7z)<br/>2.注解方式实现多对多映射[<img src="./image/download.png" height="15" />下载](./ch06-many-to-many-mapping/ch06-demo-02.7z)|
|第七章|Hibernate操作持久化对象 |- Session缓存<br/>- Hibernate对象的生命周期<br/>- Hibernate操作持久化对象|[<img src="./image/presentation.png" height="15" />查看](./ch07-manage-persistant-object/ch07-manage-persistant-object.pdf) <br/>[<img src="./image/download.png" height="15" />下载](./meterials/slides/ch07-manage-persistant-object.pptx)| |
|第八章|Hibernate检索方式 |- Hibernate检索方式<br/>- Hibernate检索策略|[<img src="./image/presentation.png" height="15" />查看](./ch08-retrieval-mode/ch08-retrieval-mode.pdf) <br/>[<img src="./image/download.png" height="15" />下载](./meterials/slides/ch08-retrieval-mode.pptx)|1.检索方式[<img src="./image/download.png" height="15" />下载](./ch08-retrieval-mode/ch08-demo-01.7z)<br/>2.检索策略[<img src="./image/download.png" height="15" />下载](./ch08-retrieval-mode/ch08-demo-02.7z)|


