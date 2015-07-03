Gradle - Comsat Spring 4 MVC Hello World
========================================
Template for Comsat Spring 4 MVC + JSP view + Annotation configuration, using Gradle.

###1. Technologies used
* Cargo with Tomcat 7 or 8
* Gradle 2
* Comsat with Spring Framework 4.1.6.RELEASE (Spring controller requests will be served by more efficient Quasar fibers rather than Java threads)
* JSTL 1.2
* Logback 1.1.3
* Boostrap 3

###2. To Run this project locally
```shell
$ git clone https://github.com/circlespainter/spring4-mvc-gradle-annotation-hello-world
$ gradle [-Penv=tomcat7] cargoRunLocal
```
Access ```http://localhost:8080/spring4-mvc-gradle-annotation-hello-world/hello/<yourname>```

###4. Project Demo
Please refer to this article [Gradle - Spring 4 MVC Hello World + Annotation ](http://www.mkyong.com/spring-mvc/gradle-spring-4-mvc-hello-world-example-annotation/)
