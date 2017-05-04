# MAXMLRPC
xmlrpc for android

导入xmlrpc 两种方法：
方法一：
修改项目build.gradle
```
allprojects {
    repositories {
        jcenter()
        maven { url 'https://jitpack.io' }
    }
}
```
修改src目录下的build.gradle
```
dependencies {
    compile 'com.android.support:appcompat-v7:25.1.1'
    compile 'com.github.mikedream89:MAXMLRPC:1.0.0'
}
```
方法二：
　maven 导入：
 ```
 <dependency>
  <groupId>com.codertta</groupId>
  <artifactId>xmlrpc</artifactId>
  <version>1.0.0</version>
  <type>pom</type>
</dependency>
```
gradle 导入：
```
compile 'com.codertta:xmlrpc:1.0.0'
```
