
[github搜索排名](https://github.com/trending)

[Android 开源项目](https://github.com/Trinea/android-open-project#%E7%AC%AC%E4%B8%89%E9%83%A8%E5%88%86-%E4%BC%98%E7%A7%80%E9%A1%B9%E7%9B%AE)

[Android 开源组件和第三方库汇总](https://blog.csdn.net/renjianhhong/article/details/51798874)

[优秀的控件UI库](https://github.com/wasabeef/awesome-android-ui)

[优秀的Android资源收集与整理](https://github.com/AlanCheen/Android-Resources)

[java面试：Snailclimb/JavaGuide](https://github.com/Snailclimb/JavaGuide)//6.4K

[android面试：The top Internet companies android interview questions and answers](http://www.jackywang.tech/AndroidInterview-Q-A/)

[android面试：guoxiaoxing/android-interview](https://github.com/guoxiaoxing/android-interview) //1.2K

[关于Android分享的目录 - 送给开发者的一份礼物](https://www.jianshu.com/p/780658b79227)

[2017Android面试回忆录](https://github.com/soulrelay/InterviewMemoirs)

[Android 技能图谱学习路线](https://www.jianshu.com/p/88e32ef66ef2)

[2019校招Android面试题解1.0（中篇）](https://www.jianshu.com/p/2dd855aa1938)

[2017上半年技术文章集合—184篇文章分类汇总](https://blog.csdn.net/androidstarjack/article/details/77923753)

# 六个可以让代码变得更整洁的 Android 库

1.butterknife

2.icepick

3.Dart 和Henson

4.Parceler

5.Timber

6.Dagger和Dagger2


# 常见库汇总

[Android主流UI开源库整理](https://www.jianshu.com/p/47a4a7b99364)

[Android 开源项目分类汇总](https://github.com/Trinea/android-open-project)

[List of Android UI/UX Libraries](https://github.com/wasabeef/awesome-android-ui)

# 大神的GitHub


[JessYan](https://github.com/JessYanCoding)

[jeasonlzy](https://github.com/jeasonlzy)

[鸿洋：hongyangAndroid](https://github.com/hongyangAndroid)

[扔物线：rengwuxian](https://github.com/rengwuxian)

[代码家：daimajia](https://github.com/daimajia)

[yangchong211](https://github.com/yangchong211)

[android开发艺术探索作者：任玉刚的CSDN](https://blog.csdn.net/singwhatiwanna)


# 快速开发框架

[TommyLemon/Android-ZBLibrary](https://github.com/TommyLemon/Android-ZBLibrary) //2.8K

[jiangqqlmj/FastDev4Android](https://github.com/jiangqqlmj/FastDev4Android)     //2.6K

[一些开源工具类（作者GitHubdemo挺好）](https://github.com/tuacy/ViewMove/blob/master/common/src/main/java/com/pilot/common/utils/TimeUtils.java)

# 优秀项目

[优秀项目](https://github.com/Ablexq/MyAsDependency/blob/master/%E4%BC%98%E7%A7%80%E9%A1%B9%E7%9B%AE.md)

# 网络相关

[网络相关](https://github.com/Ablexq/MyAsDependency/blob/master/%E7%BD%91%E7%BB%9C%E7%9B%B8%E5%85%B3.md)

# 优秀的库

#### <font color="#ff0000">基础</font>

```
//---------------------------------------基础------------------------------------------------

    compile 'com.android.support:appcompat-v7:25.3.1'
    compile 'com.android.support:support-v4:25.3.1'
    compile 'com.android.support:recyclerview-v7:25.3.1'
    compile 'com.android.support:design:25.3.1'
    compile 'com.android.support:cardview-v7:25.3.1'
    compile 'com.android.support:support-vector-drawable:25.3.1'
    compile 'com.android.support:palette-v7:25.3.1'
    compile 'com.android.support:percent:25.3.1'
    compile 'com.android.support:support-annotations:25.3.1'
    //分包
    compile 'com.android.support:multidex:1.0.1'
```



#### <font color=#ff0000>activity状态保存</font>


```
//icepick:避免在Activity恢复时重新设置状态的麻烦
  compile 'frankiesardo:icepick:3.2.0'
  provided 'frankiesardo:icepick-processor:3.2.0'
//3.7K
```
https://github.com/frankiesardo/icepick 


#### <font color="#ff0000">activity侧滑返回</font>

bingoogolapple/BGASwipeBackLayout-Android
Android Activity 滑动返回。支持微信滑动返回样式、横屏滑动返回、全屏滑动返回
```
//activity侧滑返回
    compile 'cn.bingoogolapple:bga-swipebacklayout:1.1.9'
//1.4K
```
https://github.com/bingoogolapple/BGASwipeBackLayout-Android    


ikew0ng/SwipeBackLayout
可用SwipeBackLayout实现滑动关闭当前Activity
```
    compile 'me.imid.swipebacklayout.lib:library:1.1.0'
//5.3K
```
https://github.com/ikew0ng/SwipeBackLayout

#### <font color="#ff0000">fragment管理</font>

```
//fragment管理
    compile 'me.yokeyword:fragmentation:1.3.6'
//7.2K
```
https://github.com/YoKeyword/Fragmentation  


#### <font color="#ff0000">工具类</font>

```
//工具类
    implementation 'com.blankj:utilcode:1.20.3'
//19.9K
```
https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/README-CN.md     
https://github.com/Blankj/AndroidUtilCode/blob/master/subutil/README-CN.md


#### <font color="#ff0000">google推送</font>

```
//firebase的功能包括推送通知，云存储，活动监视，远程部署,Google推出的一个云端服务，使用免费但须翻墙
    compile 'com.google.firebase:firebase-core:9.0.2'
```

#### <font color="#ff0000">序列化</font>

```
//Parceler 是一个代码代码生成器包，用于生成Android Parcelable 模板代码。
    compile 'org.parceler:parceler-api:1.1.11'
    annotationProcessor 'org.parceler:parceler:1.1.11'
//3.3K
```
https://github.com/johncarl81/parceler      


#### <font color="#ff0000">java解析HTML</font>

```
//jsoup
    compile 'org.jsoup:jsoup:1.11.3'
```
https://jsoup.org/download  
http://www.open-open.com/jsoup/     使用文档



#### 路由
```
//alibaba/ARouter
//7.5K
```
https://github.com/alibaba/ARouter  
中文文档：
https://github.com/alibaba/ARouter/blob/master/README_CN.md


#### 文件操作
```
   // io
    api 'commons-io:commons-io:2.6'
```


#### 时间格式化
```
    compile 'org.ocpsoft.prettytime:prettytime:4.0.1.Final'
//965
```
https://github.com/ocpsoft/prettytime


```
    api 'joda-time:joda-time:2.9.9'
```



#### Android Signature V2 Scheme签名下的新一代渠道包打包神器
```
    compile 'com.meituan.android.walle:library:1.1.6'
//3.6K
```
https://github.com/Meituan-Dianping/walle


#### Android资源混淆工具(微信团队)
5.1K
https://github.com/shwenzhang/AndResGuard/blob/master/README.zh-cn.md



### 状态切换
```
//内容界面
//加载数据中
//加载数据错误
//加载后没有数据
//没有网络
    compile 'cn.yc:YCStateLib:1.1.5
//95
```
https://github.com/yangchong211/YCStateLayout

状态切换布局，使用场景（网路数据请求的时候，正在请求数据，请求数据失败，请求数据成功多种状态下显示不同的布局）。
https://github.com/tuacy/StateSwitchLayout

Android 加载成功、加载失败、加载中、无数据四个不同界面的切换
https://blog.csdn.net/zhaozhuzi/article/details/73822894












