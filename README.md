
# FastDFS java client SDK

FastDFS Java Client API may be copied only under the terms of the BSD license.

## 使用ant从源码构建

```
ant clean package
```

## 使用maven从源码安装

```
mvn clean install
```

## 使用maven从jar文件安装
```
mvn install:install-file -DgroupId=org.csource -DartifactId=fastdfs-client-java -Dversion=${version} -Dpackaging=jar -Dfile=fastdfs-client-java-${version}.jar
```

## 在您的maven项目pom.xml中添加依赖

```xml
<dependency>
    <groupId>org.csource</groupId>
    <artifactId>fastdfs-client-java</artifactId>
    <version>1.29-SNAPSHOT</version>
</dependency>
```

### 项目已经构建好，可直接手动将fastdfs添加到maven本地仓库

```
在fastdfs\fastdfs-client-java\target下找fastdfs-client-java-1.29-SNAPSHOT.jar
```

###### (手动建立文件夹即可，完成后再刷新一下配置)

```
C:\repository\org\csource\fastdfs-client-java\1.29-SNAPSHOT
```
