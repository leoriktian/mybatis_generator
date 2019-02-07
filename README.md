# mybatis_generator
Idea生成mybatis逆向工程
步骤:
Intellij IDEA中使用MyBatis-generator 自动生成MyBatis代码
  1、在idea中安装MyBatis-generator插件,点击 File -> Settings -> Plugins，输入mybatis-generator找到这个插件
  2、创建一个maven工程，此过程略
  3、在pom文件中添加代码
  4、在resources中建立generatorConfig.xml 
  5、点击 Maven Projects ->双击 mybatis-generator下的mybatis_generator:genertate会
     自动生成MyBatis代码(mapper接口/mapper.xml/po类)


