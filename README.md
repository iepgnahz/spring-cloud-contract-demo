tips：
使用IDEA生成spring boot项目，创建项目时，会让你选择项目中要使用的工具，这时候你可能会选择：web、spring-cloud-contract
但是请注意，使用这种方式会自动引入版本先对比较高的包，可能和网上的教程有冲突，因此最好选择使用官网上给的gradle 配置

项目启动
provider-service：
  指令：
  ./gradlew clean test
  测试运行成功之后执行
  ./gradlew install 
  验收：
  查看 ~.m2/repository目录  存在pei目录
consumer:
  指令：
  ./gradlew clean test
  验收
  测试通过


