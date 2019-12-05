## 后台服务
该前端代码的后台部分是在d盘下JavaProject文件夹中的demo2
## 笔记整理
### 后台部分
#### 整体框架
该后台使用springboot整合jpa实现
#### 引入lombok.jar
使用范围：在entity包下面的opeResult.java中使用。
使用目的：使用注解方式的get和set，不需要再写方法。
#### 引入mysql-connector-java-8.0.17.jar
适用范围：application.properties中配置数据库(spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver)使用。
使用目的：连接MySQL数据库
#### 关于启动类DemoApplication.java的说明
带有注解的类要放在该类的同级或者子级目录下，否则访问不到。该项目使用到跨域，因此对该类做了代码添加。
参考连接：
* [springboot配置允许跨域访问](https://blog.csdn.net/syystx/article/details/82850393)
* [Springboot后台设置允许跨域的方法](https://blog.csdn.net/hlp4207/article/details/80870716)

### 前台部分
#### vue的使用
该项目是通过script引入vue的，并没有使用vue脚手架，因此elementui中的export default并不能使用。
#### 前端框架elementui的使用
对于登录注册界面使用elementui，参考表单提交部分，和vue是相关联的，因此要创建vue对象才能显示控件。


