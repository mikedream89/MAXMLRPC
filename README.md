# MAXMLRPC
xmlrpc for android

gradle 导入包
修改项目build.gradle
allprojects {
    repositories {
        jcenter()
        maven { url 'https://jitpack.io' }
    }
}
修改src目录下的build.gradle
dependencies {
    compile 'com.android.support:appcompat-v7:25.1.1'
    compile 'com.github.mikedream89:MAXMLRPC:1.0.0'
}
