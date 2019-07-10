目前比较常见的Android开源托管地址有如下几种：


|类型|	特点|
|--|--|
|Maven Central|	发布过程繁杂冗长。|
|jCenter	|jCenter貌似稍微简单一点，但也不是省油的灯|
|自定义仓库	|企业内部可能会见到。|

以上三种方式用起来都挺难受的，于是乎JitPack横空出世，让你能优雅地发布属于自己的开源库了，首先对JitPack做一个简短的介绍。

[JitPack地址](https://jitpack.io/)

### JitPack是什么？
```
JitPack是一个自定义的Maven仓库。

```

### JitPack安全吗？
```
个人觉得还是比较安全的，毕竟开源库都是给大家用的，源码都能分享出来，如果你是担心它在里面插入恶意代码的话，在AndroidStudio的 External Libraies里面能够看到反编译的依赖库的源码，可以查看一下。

```

### JitPack好处都有啥?
```
省时间，省时间，省时间

```

### AS发布安卓开源库到JitPack的步骤（以我自己的开源库MyUtils为例）
#### 第一步：新建一个Android项目（步骤略）
#### 第二步：在项目中添加一个Library

##### 添加Library操作步骤：File --> New -->New Module   
![](https://raw.githubusercontent.com/xiashi/my-photo-gallery/master/Android_jar/step1.png)

点击Next后，然后填入你Library的名称等等..  即可创建完成Library

#### 第三步：配置Library的build.gradle
##### 添加如下两行配置至Library的build.gradle
    
    apply plugin: 'com.github.dcendents.android-maven'
    group='com.github.xiashi'

![](https://raw.githubusercontent.com/xiashi/my-photo-gallery/master/Android_jar/step3.png)

#### 第四步：配置Project的build.gradle

##### 添加如下配置至Project的build.gradle(plugin的版本用最新的，现在最新的版本是2.1)

    classpath 'com.github.dcendents:android-maven-gradle-plugin:2.1'
    

![](https://raw.githubusercontent.com/xiashi/my-photo-gallery/master/Android_jar/step2.png)

#### 第五步：提交项目到github

#### 第六步: Release你的仓库或者给你的仓库打一个Tag(重点)
##### 1.点击图示进入Release界面
![](https://raw.githubusercontent.com/xiashi/my-photo-gallery/master/Android_jar/step4.png)


##### 2.创建一个Release或Tag
![](https://raw.githubusercontent.com/xiashi/my-photo-gallery/master/Android_jar/step5.png)
##### 3.填写基本信息
![](https://raw.githubusercontent.com/xiashi/my-photo-gallery/master/Android_jar/step6.png)

#### 第七步：将你github的仓库地址依赖到JitPack
[JitPack地址](https://jitpack.io/)

![](https://raw.githubusercontent.com/xiashi/my-photo-gallery/master/Android_jar/step7.png)

###### 在JitPack依赖你的github开源地址后，就会自动生成引用该仓库的配置信息

![](https://raw.githubusercontent.com/xiashi/my-photo-gallery/master/Android_jar/step8.png)

#### 第八步：将生成的配置信息,编辑在项目的README中

![](https://raw.githubusercontent.com/xiashi/my-photo-gallery/master/Android_jar/step9.png)