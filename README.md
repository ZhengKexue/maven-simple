# maven-simple
maven-simple例子，主要是测试一下集成使用 https://jitpack.io/ 发布maven中央仓库

 
Step 1. Add the JitPack repository 到你的工程pom文件或者setting.xml文件
```
<repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
	</repositories>
  
```
	
Step 2. 添加依赖
```
	<dependency>
	    <groupId>com.github.ZhengKexue</groupId>
	    <artifactId>maven-simple</artifactId>
	    <version>release-1.0.0-8d3bd3b647-1</version>
	</dependency>
```
