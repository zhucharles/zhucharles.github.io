若要使用servlet注解，必须导入servlet-api.jar

在Eclipse中添加Servlet-api.jar的方法

方法一：
点击窗口->首选项->java->构建路径－>类路径变量->新建；
将你的tomcat目录下的common/lib/servlet.jar加进来。
如果你建立了一个tomcatproject它会自动加进来的，如果没有的话你也可以通过手动来加入，选中你刚才建的项目右击->属性->java构建路径－>添加变量;将你刚才加入的servlet.jar变量加进来就行了。
如何在Eclipse中添加Servlet-api.jar的方法
正确的加载servlet-api.jar的方法如下：

1. 右击项目工程名称
2. Properties
3. Jvav Build Path
4. Libraries
5. Add External JARS
6. 找到“C:\Program Files\Apache Software Foundation\Tomcat 5.0\common\lib\servlet-api.jar”
7. 添加既可
 
方法二：

 窗口->首选项->java  ->   已安装的jre  ->   编辑  -> 添加外部的jar   (把servlet-api.jar加进来就ok了)
