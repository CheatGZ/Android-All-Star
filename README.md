记一些项目中遇到的第三方组件或框架，如果以下条目有更好的替代品，欢迎提出！Star and Respect All!

[GitHub Pages](https://cheatgz.github.io/Android-All-Star/)

- [界面](#界面)
  * [图片](#图片)
    + [android-gif-drawable](#android-gif-drawable)
    + [CircleImageView](#circleimageview)
    + [RoundedImageView](#roundedimageview)
    + [PhotoView](#photoview)
    + [subsampling-scale-image-view](#subsampling-scale-image-view)
    + [uCrop](#ucrop)
    + [PictureSelector](#pictureselector)
  * [文本](#文本)
    + [richeditor-android](#richeditor-android)
    + [TextSurface](#textsurface)
  * [弹窗](#弹窗)
    + [BaseDialog](#basedialog)
    + [material-dialogs](#material-dialogs)
    + [Toasty](#toasty)
  * [状态栏](#状态栏)
    + [ImmersionBar](#immersionbar)
    + [banner](#banner)
  * [指示器](#指示器)
    + [MagicIndicator](#magicindicator)
  * [图表](#图表)
    + [MPAndroidChart](#mpandroidchart)
    + [TableView](#tableview)
  * [角标](#角标)
    + [BGABadgeView-Android](#bgabadgeview-android)
  * [选择器](#选择器)
    + [Android-PickerView](#android-pickerview)
  * [欢迎页](#欢迎页)
    + [AppIntro](#appintro)
  * [菜单](#菜单)
    + [MaterialDrawer](#materialdrawer)
  * [日历](#日历)
    + [CalendarView](#calendarview)
  * [高斯模糊](#高斯模糊)
    + [blurkit-android](#blurkit-android)
  * [webview](#webview)
    + [AgentWeb](#agentweb)
  * [布局](#布局)
    + [vlayout](#vlayout)
    + [AndroidAutoSize](#androidautosize)
  * [通信](#通信)
    + [ARouter](#arouter)
    + [EventBus](#eventbus)
  * [其它](#其它)
    + [BaseRecyclerViewAdapterHelper](#baserecyclerviewadapterhelper)
    + [MultiLanguages](#multilanguages)
    + [QMUI_Android](#qmui_android)
    + [SmartRefreshLayout](#smartrefreshlayout)
- [图片](#图片)
  * [图片加载](#图片加载)
    + [Glide](#glide)
    + [fresco](#fresco)
    + [Android-Universal-Image-Loader](#android-universal-image-loader)
  * [图片处理](#图片处理)
    + [glide-transformations](#glide-transformations)
    + [Luban](#luban)
    + [android-gpuimage](#android-gpuimage)
- [视频](#视频)
  * [播放器](#播放器)
    + [ijkplayer](#ijkplayer)
    + [GSYVideoPlayer](#gsyvideoplayer)
- [网络](#网络)
  * [json](#json)
    + [gson](#gson)
    + [fastjson](#fastjson)
  * [框架](#框架)
    + [retrofit](#retrofit)
    + [okhttp](#okhttp)
    + [volley](#volley)
    + [Java-WebSocket](#java-websocket)
  * [文件下载](#文件下载)
    + [FileDownloader](#filedownloader)
    + [okdownload](#okdownload)
    + [PRDownloader](#prdownloader)
- [存储](#存储)
  + [MMKV](#mmkv)
- [优化](#优化)
  + [leakcanary](#leakcanary)
- [日志](#日志)
  + [logger](#logger)
  + [timber](#timber)
- [权限](#权限)
  + [PermissionX](#permissionx)
- [不再推荐](#不再推荐)
  * [~~AndroidEventBus~~](#androideventbus)
  * [~~BadgeView~~](#badgeview)
  * [~~ButterKnife~~](#butterknife)
  * [~~CardSwipeLayout~~](#cardswipelayout)
  * [~~greenDAO~~](#greendao)
  * [~~MVPArms~~](#mvparms)
  * [~~NineOldAndroids~~](#nineoldandroids)
  * [~~NumberProgressBar~~](#numberprogressbar)
  * [~~picasso~~](#picasso)
  * [~~ViewPagerIndicator~~](#viewpagerindicator)
  * [~~Matisse~~](#matisse)

条目详细格式如下：

```
框架/组件       //框架或组件的Github地址，点击查看
GitHub 🌟：    //GitHub star星数
项目简介：      //框架或组件的简介
项目参考Blog：  //框架或组件可以参考如何使用的Blog
项目使用        //配置或添加框架、组件依赖
    implementation 'xx.xxx:xxx:x.x.x'
```

## 界面

### 图片

#### [android-gif-drawable](https://github.com/koral--/android-gif-drawable)

项目简介：Views and Drawable for displaying animated GIFs on Android

GitHub 🌟：8.7k

项目参考Blog：[android-gif-drawable教程](https://blog.csdn.net/feather_wch/article/details/79558240)

项目引入

```
    dependencies {
        ...
        implementation 'pl.droidsonroids.gif:android-gif-drawable:1.2.22'
    }
```

#### [CircleImageView](https://github.com/hdodenhof/CircleImageView)

项目简介：A fast circular ImageView perfect for profile images. 

GitHub 🌟：13.8k

项目参考Blog：[Android之CircleImageView使用(原创)](https://my.oschina.net/u/4410490/blog/3583355)

项目引入

```
    dependencies {
        ...
        implementation 'de.hdodenhof:circleimageview:3.1.0'
    }
```

#### [RoundedImageView](https://github.com/vinc3m1/RoundedImageView)

项目简介：A fast ImageView that supports rounded corners, ovals, and circles.

GitHub 🌟：6.2k

项目参考Blog：[Android 第三方RoundedImageView设置各种圆形、方形头像](https://blog.csdn.net/shenggaofei/article/details/83793536)

项目引入

```
    dependencies {
        ...
        implementation 'com.makeramen:roundedimageview:2.3.0'
    }
```

#### [PhotoView](https://github.com/chrisbanes/PhotoView)

项目简介：Implementation of ImageView for Android that supports zooming, by various touch gestures.

GitHub 🌟：17.6k

项目参考Blog：[Android UI Libs之PhotoView](https://www.jianshu.com/p/680f4859a000)

项目引入

```
    implementation 'com.github.chrisbanes:PhotoView:latest.release.here'
```

Add this in your root build.gradle file (not your module build.gradle file):

```
    allprojects {
       repositories {
          jcenter()
          maven { url 'https://jitpack.io' }
       }
    }
    buildscript {
        repositories {
          maven { url "https://www.jitpack.io" }
       }	
    }
```

#### [subsampling-scale-image-view](https://github.com/davemorrissey/subsampling-scale-image-view)

项目简介：Android library (AAR). Highly configurable, easily extendable deep zoom view for displaying huge images without loss of detail.

GitHub 🌟：6.7k

项目参考Blog：Subsampling Scale Image View [WiKi](https://github.com/davemorrissey/subsampling-scale-image-view/wiki/02.-Displaying-images)

项目引入

```
    dependencies {
        ...
        implementation 'com.davemorrissey.labs:subsampling-scale-image-view:3.10.0' // for support lib
        implementation 'com.davemorrissey.labs:subsampling-scale-image-view-androidx:3.10.0' // for androidx
    }
```

#### [uCrop](https://github.com/Yalantis/uCrop)

项目简介：Image Cropping Library for Android

GitHub 🌟：10.6k

项目参考Blog：[Android7.0拍照以及使用uCrop裁剪](https://juejin.cn/post/6844903495506591757)

项目引入

```
    dependencies {
        ...
        implementation 'com.github.yalantis:ucrop:2.2.6' //lightweight general solution
		implementation 'com.github.yalantis:ucrop:2.2.6-native' //get power of the native code to preserve image quality (+ about 1.5 MB to an apk size)
    }
```

#### [PictureSelector](https://github.com/LuckSiege/PictureSelector)

项目简介：Picture Selector Library for Android or 多图片选择器

GitHub 🌟：10.1k

项目参考Blog：[Android 选择图片、上传图片之PictureSelector](https://blog.csdn.net/yechaoa/article/details/79291552)

项目引入

```
    implementation 'com.github.LuckSiege.PictureSelector:picture_library:v2.6.0'
```

```
    allprojects {
       repositories {
          jcenter()
          maven { url 'https://jitpack.io' }
       }
    }
```

### 文本

#### [richeditor-android](https://github.com/wasabeef/richeditor-android)

项目简介：RichEditor for Android is a beautiful Rich Text WYSIWYG Editor for Android.

GitHub 🌟：5.4k

项目参考Blog：[移动端强大的富文本编辑器richeditor-android](https://www.cnblogs.com/demodashi/p/10486780.html)

项目引入

```
	repositories {
  		mavenCentral()
	}

    dependencies {
        ...
        implementation 'jp.wasabeef:richeditor-android:2.0.0'
    }
```

#### [TextSurface](https://github.com/elevenetc/TextSurface)

项目简介：A little animation framework which could help you to show message in a nice looking way

GitHub 🌟：2.1k

项目参考Blog：[一个Android文字展示动画框架：TextSurface](https://www.open-open.com/lib/view/open1446797002013.html)

项目引入

```
	repositories {
    	maven { url "https://jitpack.io" }
	}
    dependencies {
        ...
        implementation 'com.github.elevenetc:textsurface:0.9.1'
    }
```
### 弹窗

#### [BaseDialog](https://github.com/AnJiaoDe/BaseDialog)

项目简介：Android BaseDialog(开发必备)动画、加载进度、阴影、上下左右中 进入

GitHub 🌟：163

项目参考Blog：[Android BaseDialog(开发必备)动画、加载进度、阴影](https://blog.csdn.net/confusing_awakening/article/details/78332459)

项目引入

```
    implementation 'com.github.AnJiaoDe:BaseDialog:V1.1.8'
```

```
    allprojects {
       repositories {
          jcenter()
          maven { url 'https://jitpack.io' }
       }
    }
```

#### [material-dialogs](https://github.com/afollestad/material-dialogs)

项目简介：😍 A beautiful, fluid, and extensible dialogs API for Kotlin & Android.

GitHub 🌟：18.7k

项目参考Blog：[material-dialogs/documentation](https://github.com/afollestad/material-dialogs/tree/main/documentation)

项目引入

```
    dependencies {
        ...
        implementation 'com.afollestad.material-dialogs:core:3.3.0'
    }
```

#### [Toasty](https://github.com/GrenderG/Toasty)

项目简介：The usual Toast, but with steroids 💪

GitHub 🌟：6.1k

项目参考Blog：[Usage](https://github.com/GrenderG/Toasty#usage)

项目引入

```
    dependencies {
        ...
        implementation 'com.github.GrenderG:Toasty:1.5.0'
    }
```

### 状态栏

#### [ImmersionBar](https://github.com/gyf-dev/ImmersionBar)

项目简介：Android 4.4以上沉浸式状态栏和沉浸式导航栏管理

GitHub 🌟：9.5k

项目参考Blog：[android4.4以上沉浸式状态栏和导航栏实现以及Bar的其他管理](https://www.jianshu.com/p/2a884e211a62)

项目引入

```
    dependencies {
        ...
        // 基础依赖包，必须要依赖
		implementation 'com.gyf.immersionbar:immersionbar:3.0.0'
		// fragment快速实现（可选）
		implementation 'com.gyf.immersionbar:immersionbar-components:3.0.0'
		// kotlin扩展（可选）
		implementation 'com.gyf.immersionbar:immersionbar-ktx:3.0.0'
    }
```

### 轮播图

#### [banner](https://github.com/youth5201314/banner)

项目简介：只做一个可以自定义的轮播容器，不侵入UI ———— Banner 2.0

GitHub 🌟：11.1k

项目参考Blog：[Banner2.0 GitHub介绍](https://github.com/youth5201314/banner)

项目引入

```
    implementation 'com.youth.banner:banner:2.1.0'
```

### 指示器

#### [MagicIndicator](https://github.com/hackware1993/MagicIndicator)

项目简介：强大、可定制、易扩展的 ViewPager 指示器框架。是ViewPagerIndicator、TabLayout、PagerSlidingTabStrip的最佳替代品

GitHub 🌟：8.6k

项目参考Blog：[MagicIndicator系列之一 —— 使用MagicIndicator打造千变万化的ViewPager指示器](https://www.jianshu.com/p/2865812fed41)

项目引入

```
    repositories {
        ...
        maven {
            url "https://jitpack.io"
        }
    }

    dependencies {
        ...
        implementation 'com.github.hackware1993:MagicIndicator:1.6.0' // for support lib
        implementation 'com.github.hackware1993:MagicIndicator:1.7.0' // for androidx
    }
```
### 图表

#### [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart)

项目简介：A powerful 🚀 Android chart view / graph view library, supporting line- bar- pie- radar- bubble- and candlestick charts as well as scaling, panning and animations.

GitHub 🌟：33.1k

项目参考Blog：[detailed video tutorials(付费视频)](https://weeklycoding.com/downloads/)、[MPAndroidChart Documentation](https://weeklycoding.com/mpandroidchart-documentation/)

项目引入

```
    repositories {
        ...
        maven {
            url "https://jitpack.io"
        }
    }

    dependencies {
    	implementation 'com.github.PhilJay:MPAndroidChart:v3.1.0'
    }
```

#### [TableView](https://github.com/evrencoskun/TableView)

项目简介：TableView is a powerful Android library for displaying complex data structures and rendering tabular data composed of rows, columns and cells

GitHub 🌟：2.8k

项目参考Blog：[Welcome to the Documentation of the TableView library](https://github.com/evrencoskun/TableView/wiki)

项目引入

```
	dependencies {
    	implementation 'com.evrencoskun.library:tableview:0.8.9.4'
	}
```

### 角标

#### [BGABadgeView-Android](https://github.com/bingoogolapple/BGABadgeView-Android)

项目简介：Android 徽章控件

GitHub 🌟：2.4k

项目参考Blog：[初始化徽章控件](https://github.com/bingoogolapple/BGABadgeView-Android#初始化徽章控件)

项目引入

```
	//把 maven { url 'https://jitpack.io' } 加入到 repositories 中
	repositories {
    	maven { url "https://jitpack.io" }
	}
	
    dependencies {
        ...
        implementation 'com.github.bingoogolapple.BGABadgeView-Android:api:latestVersion'
    	annotationProcessor 'com.github.bingoogolapple.BGABadgeView-Android:compiler:latestVersion'
    }
```

### 选择器

#### [Android-PickerView](https://github.com/Bigkoo/Android-PickerView)

项目简介：This is a picker view for android , support linkage effect, timepicker and optionspicker.（时间选择器、省市区三级联动）

GitHub 🌟：12.7k

项目参考Blog：[PickerView--仿ios滚轮时间选择、城市选择效果](https://blog.csdn.net/wangwo1991/article/details/85036891)

项目引入

```
    implementation 'com.contrarywind:Android-PickerView:4.1.9'
```

### 欢迎页

#### [AppIntro](https://github.com/AppIntro/AppIntro)

项目简介：Make a cool intro for your Android app.

GitHub 🌟：9.7k

项目参考Blog：[Basic usage](https://github.com/AppIntro/AppIntro#basic-usage)

项目引入

```
	repositories {
    	maven { url "https://jitpack.io" }
	}

    dependencies {
        ...
        implementation 'com.github.AppIntro:AppIntro:4.2.3' // for support lib
        implementation 'com.github.AppIntro:AppIntro:6.1.0' // for androidx
    }
```

### 菜单

#### [MaterialDrawer](https://github.com/mikepenz/MaterialDrawer)

项目简介：The flexible, easy to use, all in one drawer library for your Android project. Now brand new with material 2 design

GitHub 🌟：11.3k

项目参考Blog：[Android, Using Navigation Drawer Across Multiple Activities: The easiest way.](https://medium.com/android-news/android-using-navigation-drawer-across-multiple-activities-the-easiest-way-b011f152aebd)

项目引入

```
    implementation "com.mikepenz:materialdrawer:${lastestMaterialDrawerRelease}"

	//required support lib modules
	implementation "androidx.appcompat:appcompat:${versions.appcompat}"
	implementation "androidx.recyclerview:recyclerview:${versions.recyclerView}"
	implementation "androidx.annotation:annotation:${versions.annotation}"
	implementation "com.google.android.material:material:${versions.material}"
	implementation "androidx.constraintlayout:constraintlayout:${versions.constraintLayout}"

	// Add for NavController support
	implementation "com.mikepenz:materialdrawer-nav:${lastestMaterialDrawerRelease}"

	// Add for Android-Iconics support
	implementation "com.mikepenz:materialdrawer-iconics:${lastestMaterialDrawerRelease}"
```

### 日历

#### [CalendarView](https://github.com/huanghaibin-dev/CalendarView)

项目简介：Android上一个优雅、万能自定义UI、支持周视图、自定义周起始、性能高效的日历控件，支持热插拔实现的UI定制！

GitHub 🌟：7.5k

项目参考Blog：[CalendarView使用详细文档](https://github.com/huanghaibin-dev/CalendarView/blob/master/QUESTION_ZH.md)

项目引入

```
    dependencies {
        ...
        implementation 'com.haibin:calendarview:3.6.8' // for support lib
        implementation 'com.haibin:calendarview:3.7.1' // for androidx
    }
```

### 高斯模糊

#### [blurkit-android](https://github.com/CameraKit/blurkit-android)

项目简介：Android上一个优雅、万能自定义UI、支持周视图、自定义周起始、性能高效的日历控件，支持热插拔实现的UI定制！

GitHub 🌟：3.4k

项目参考Blog：[Usage](https://github.com/CameraKit/blurkit-android#usage)

项目引入

```
    dependencies {
        ...
        implementation 'io.alterac.blurkit:blurkit:1.1.0'
    }
```

### webview

#### [AgentWeb](https://github.com/Justson/AgentWeb)

项目简介：AgentWeb is a powerful library based on Android WebView.

GitHub 🌟：8k

项目参考Blog：[WebView 性能和用户体验优化](https://www.jianshu.com/p/fc7909e24178)

项目引入

```
    dependencies {
        ...
        implementation 'com.just.agentweb:agentweb:4.1.4' // (必选)
		implementation 'com.just.agentweb:filechooser:4.1.4'// (可选)
		implementation 'com.download.library:Downloader:4.1.4'// (可选) // for support lib
		
        implementation 'com.just.agentweb:agentweb-androidx:4.1.4' // (必选)
		implementation 'com.just.agentweb:filechooser-androidx:4.1.4'// (可选)
		implementation 'com.download.library:downloader-androidx:4.1.4'// (可选) // for androidx
    }
```

### 通信

#### [ARouter](https://github.com/alibaba/ARouter)

项目简介：一个用于帮助 Android App 进行组件化改造的框架 —— 支持模块间的路由、通信、解耦

GitHub 🌟：13k

项目参考Blog：[ARouter/README_CN.md](https://github.com/alibaba/ARouter/blob/master/README_CN.md)

项目引入

```
    android {
        defaultConfig {
            ...
            javaCompileOptions {
                annotationProcessorOptions {
                    arguments = [AROUTER_MODULE_NAME: project.getName()]
                }
            }
        }
    }

    dependencies {
        // 替换成最新版本, 需要注意的是api
        // 要与compiler匹配使用，均使用最新版可以保证兼容
        compile 'com.alibaba:arouter-api:x.x.x'
        annotationProcessor 'com.alibaba:arouter-compiler:x.x.x'
        ...
    }
    // 旧版本gradle插件(< 2.2)，可以使用apt插件，配置方法见文末'其他#4'
    // Kotlin配置参考文末'其他#5'
```

#### [EventBus](https://github.com/greenrobot/EventBus)

项目简介：Event bus for Android and Java that simplifies communication between Activities, Fragments, Threads, Services, etc. Less code, better quality

GitHub 🌟：23.3k

项目参考Blog：[Android EventBus 的使用](https://www.jianshu.com/p/e7d5c7bda783)

项目引入

```
  implementation 'org.greenrobot:eventbus:3.2.0'
```

### 布局

####  [vlayout](https://github.com/alibaba/vlayout)

项目简介：Project vlayout is a powerfull LayoutManager extension for RecyclerView, it provides a group of layouts for RecyclerView. Make it able to handle a complicate situation when grid, list and other layouts in the same recyclerview.

GitHub 🌟：10.7k

项目参考Blog：[vlayout--让你的多布局不再头疼](https://www.jianshu.com/p/5fb06a52a12d)

项目引入

```
    implementation ('com.alibaba.android:vlayout:1.2.8@aar') {
	    transitive = true
    }
```

#### [AndroidAutoSize](https://github.com/JessYanCoding/AndroidAutoSize)

项目简介：🔥 A low-cost Android screen adaptation solution (今日头条屏幕适配方案终极版，一个极低成本的 Android 屏幕适配方案).

GitHub 🌟：11.3k

项目参考Blog：[今日头条屏幕适配方案终极版，一个极低成本的 Android 屏幕适配方案.](https://github.com/JessYanCoding/AndroidAutoSize/blob/master/README-zh.md)

项目引入

```
    dependencies {
        ...
        implementation 'me.jessyan:autosize:1.2.1'
    }
```

### 其它 

#### [BaseRecyclerViewAdapterHelper](https://github.com/CymChad/BaseRecyclerViewAdapterHelper)

项目简介：BRVAH:Powerful and flexible RecyclerAdapter

GitHub 🌟：21.7k

项目参考Blog：[BRVAH官网](http://www.recyclerview.org/)

项目引入

```
    implementation 'com.github.CymChad:BaseRecyclerViewAdapterHelper:3.0.4'
```

#### [MultiLanguages](https://github.com/MichaelJokAr/MultiLanguages)

项目简介：Android 多语言切换（兼容8.0+） 2.0版本，一句代码完成多语言切换，现在支持第三方包里多语言切换（前提是有对应的语言资源）

GitHub 🌟：300

项目参考Blog：[MultiLanguages/README_cn.md](https://github.com/MichaelJokAr/MultiLanguages/blob/master/README_cn.md)

项目引入

在APP的build.gradle文件下引入gradle plugin

```
    buildscript {
        dependencies {
            classpath 'com.github.jokar:multi-languages.plugin:<latest-version>'
        }
    }
```

在模块的build.gradle文件中引入plugin

```
    apply plugin: 'multi-languages'
    ...
    android{
        defaultConfig { 
            multiLanguages {
                //set plugin is enable( default)
                enable = true
            }
        }
    }
    ...
    dependencies {
        implementation 'com.github.jokar:multi-languages:<latest-version>'
    }
    
```

#### [QMUI_Android](https://github.com/Tencent/QMUI_Android)

项目简介：提高 Android UI 开发效率的 UI 库

GitHub 🌟：12.8k

项目参考Blog：QMUI_Android[官网](https://qmuiteam.com/android)

项目引入

```
	//最新的库会上传到 JCenter 仓库上，请确保配置了 JCenter 仓库源
    dependencies {
        ...
        implementation 'com.qmuiteam:qmui:2.0.0-alpha10'
    }
```

#### [SmartRefreshLayout](https://github.com/scwang90/SmartRefreshLayout)

项目简介：🔥下拉刷新、上拉加载、二级刷新、淘宝二楼、RefreshLayout、OverScroll，Android智能下拉刷新框架，支持越界回弹、越界拖动，具有极强的扩展性，集成了几十种炫酷的Header和 Footer

GitHub 🌟：22.4k

项目参考Blog：[Android智能下拉刷新框架-SmartRefreshLayout](https://segmentfault.com/a/1190000010066071)

项目引入

如果使用 AndroidX 先在 gradle.properties 中添加，两行都不能少噢~

```
    android.useAndroidX=true
    android.enableJetifier=true
```

需要依赖 androidx.appcompat

```
    implementation 'androidx.appcompat:appcompat:1.0.0'                 //必须 1.0.0 以上

    implementation  'com.scwang.smart:refresh-layout-kernel:2.0.3'      //核心必须依赖
    implementation  'com.scwang.smart:refresh-header-classics:2.0.3'    //经典刷新头
    implementation  'com.scwang.smart:refresh-header-radar:2.0.3'       //雷达刷新头
    implementation  'com.scwang.smart:refresh-header-falsify:2.0.3'     //虚拟刷新头
    implementation  'com.scwang.smart:refresh-header-material:2.0.3'    //谷歌刷新头
    implementation  'com.scwang.smart:refresh-header-two-level:2.0.3'   //二级刷新头
    implementation  'com.scwang.smart:refresh-footer-ball:2.0.3'        //球脉冲加载
    implementation  'com.scwang.smart:refresh-footer-classics:2.0.3'    //经典加载
```

## 图片

### 图片加载

#### [Glide](https://github.com/bumptech/glide)

项目简介：An image loading and caching library for Android focused on smooth scrolling

GitHub 🌟：31k

项目参考Blog：[Glide使用总结](https://www.jianshu.com/p/791ee473a89b)

项目引入

```
      implementation 'com.github.bumptech.glide:glide:4.12.0'
      annotationProcessor 'com.github.bumptech.glide:compiler:4.12.0'
```

#### [fresco](https://github.com/facebook/fresco)

项目简介：An Android library for managing images and the memory they use.

GitHub 🌟：16.5k

项目参考Blog：[Fresco中文文档](https://www.fresco-cn.org/docs/index.html)

项目引入

```
    dependencies {
        ...
        implementation 'com.facebook.fresco:fresco:2.4.0'
    }
```

#### [Android-Universal-Image-Loader](https://github.com/nostra13/Android-Universal-Image-Loader)

项目简介：Powerful and flexible library for loading, caching and displaying images on Android.

GitHub 🌟：16.8k

项目参考Blog：[Home](https://github.com/nostra13/Android-Universal-Image-Loader/wiki)

项目引入

```
    dependencies {
        ...
        implementation 'com.nostra13.universalimageloader:universal-image-loader:1.9.5'
    }
```

### 图片处理

#### [glide-transformations](https://github.com/wasabeef/glide-transformations)

项目简介：An Android transformation library providing a variety of image transformations for Glide.

GitHub 🌟：9.3k

项目参考Blog：[Glide-更多图片变换，glide-transformations的使用（六）](https://blog.csdn.net/u010356768/article/details/78455117)

项目引入

```
	repositories {
  		mavenCentral()
	}

    dependencies {
        ...
        implementation 'jp.wasabeef:glide-transformations:4.3.0'
  		// If you want to use the GPU Filters
  		implementation 'jp.co.cyberagent.android:gpuimage:2.1.0'

    }
```

#### [Luban](https://github.com/Curzibn/Luban)

项目简介：Luban(鲁班)—Image compression with efficiency very close to WeChat Moments/可能是最接近微信朋友圈的图片压缩算法

GitHub 🌟：12.4k

项目参考Blog：[Android 图片压缩之-Luban的使用](https://blog.csdn.net/oZhuiMeng123/article/details/85041624)

项目引入

```
    dependencies {
        ...
        implementation 'top.zibin:Luban:1.1.8'
    }
```

#### [android-gpuimage](https://github.com/cats-oss/android-gpuimage)

项目简介：Android filters based on OpenGL (idea from GPUImage for iOS)

GitHub 🌟：7.8k

项目参考Blog：[Usage](https://github.com/cats-oss/android-gpuimage#usage)

项目引入

```
	repositories {
    	mavenCentral()
	}
	
    dependencies {
        ...
        implementation 'jp.co.cyberagent.android:gpuimage:2.x.x'
    }
```

## 视频

### 播放器

#### [ijkplayer](https://github.com/Bilibili/ijkplayer)

项目简介：Android上一个优雅、万能自定义UI、支持周视图、自定义周起始、性能高效的日历控件，支持热插拔实现的UI定制！

GitHub 🌟：28.5k

项目参考Blog：[Android 超好用的播放器——ijkplayer](https://www.jianshu.com/p/c5d972ab0309)

项目引入

```
	allprojects {
    	repositories {
        	jcenter()
    	}
	}

    dependencies {
    # required, enough for most devices.
    implementation 'tv.danmaku.ijk.media:ijkplayer-java:0.8.8'
    implementation 'tv.danmaku.ijk.media:ijkplayer-armv7a:0.8.8'

    # Other ABIs: optional
    implementation 'tv.danmaku.ijk.media:ijkplayer-armv5:0.8.8'
    implementation 'tv.danmaku.ijk.media:ijkplayer-arm64:0.8.8'
    implementation 'tv.danmaku.ijk.media:ijkplayer-x86:0.8.8'
    implementation 'tv.danmaku.ijk.media:ijkplayer-x86_64:0.8.8'

    # ExoPlayer as IMediaPlayer: optional, experimental
    implementation 'tv.danmaku.ijk.media:ijkplayer-exo:0.8.8'
}
```

#### [GSYVideoPlayer](https://github.com/CarGuo/GSYVideoPlayer)

项目简介：视频播放器（IJKplayer、ExoPlayer、MediaPlayer），HTTPS，支持弹幕，外挂字幕，支持滤镜、水印、gif截图，片头广告、中间广告，多个同时播放，支持基本的拖动，声音、亮度调节，支持边播边缓存，支持视频自带rotation的旋转（90,270之类），重力旋转与手动旋转的同步支持，支持列表播放 ，列表全屏动画，视频加载速度，列表小窗口支持拖动，动画效果，调整比例，多分辨率切换，支持切换播放器，进度条小窗口预览，列表切换详情页面无缝播放，rtsp、concat、mpeg。

GitHub 🌟：16k

项目参考Blog：[三种简单的使用方法](https://github.com/CarGuo/GSYVideoPlayer/blob/master/doc/USE.md)

项目引入

```
    dependencies {
        ...
        //A.完整版引入
		implementation 'com.shuyu:GSYVideoPlayer:8.1.2'
		
		//B.添加java和你想要的so支持
		implementation 'com.shuyu:gsyVideoPlayer-java:8.1.2'

		//是否需要ExoPlayer模式
		implementation 'com.shuyu:GSYVideoPlayer-exo2:8.1.2'

		//根据你的需求ijk模式的so
		implementation 'com.shuyu:gsyVideoPlayer-armv5:8.1.2'
		implementation 'com.shuyu:gsyVideoPlayer-armv7a:8.1.2'
		implementation 'com.shuyu:gsyVideoPlayer-arm64:8.1.2'
		implementation 'com.shuyu:gsyVideoPlayer-x64:8.1.2'
		implementation 'com.shuyu:gsyVideoPlayer-x86:8.1.2'
		
		//C.支持其他格式协议的（mpeg，rtsp, concat、crypto协议）
		//A、B普通版本支持263/264/265等，对于mpeg编码会有声音无画面情况。 C 引入的so支持mpeg编码和其他补充协议，但是so包相对变大。
		implementation 'com.shuyu:gsyVideoPlayer-java:8.1.2'

		//是否需要ExoPlayer模式
		implementation 'com.shuyu:GSYVideoPlayer-exo2:8.1.2'

		//更多ijk的编码支持
		implementation 'com.shuyu:gsyVideoPlayer-ex_so:8.1.2'
    }
```

## 网络

### json

#### [gson](https://github.com/google/gson)

项目简介：A Java serialization/deserialization library to convert Java Objects into JSON and back

GitHub 🌟：19.4k

项目参考Blog：[GSON](https://www.jianshu.com/p/75a50aa0cad1)

项目引入

```
    implementation 'com.google.code.gson:gson:2.8.6'
```

#### [fastjson](https://github.com/alibaba/fastjson)

项目简介：A fast JSON parser/generator for Java.

GitHub 🌟：23.2k

项目参考Blog：[Quick Start CN](https://github.com/alibaba/fastjson/wiki/Quick-Start-CN)

项目引入

```
    dependencies {
        ...
        implementation 'com.alibaba:fastjson:1.1.72.android'
    }
```

### 框架

#### [retrofit](https://github.com/square/retrofit)

项目简介：A type-safe HTTP client for Android and Java.

GitHub 🌟：37.9k

项目参考Blog：[Retrofit官网](https://square.github.io/retrofit/)

项目引入

```
    implementation 'com.squareup.retrofit2:retrofit:(insert latest version)'
```

#### [okhttp](https://github.com/square/okhttp)

项目简介：Square’s meticulous HTTP client for the JVM, Android, and GraalVM.

GitHub 🌟：39.7k

项目参考Blog：[OkHttp](https://square.github.io/okhttp/)

项目引入

```
    dependencies {
        ...
        implementation("com.squareup.okhttp3:okhttp:4.9.1")
    }
```

#### [volley](https://github.com/google/volley)

项目简介：Volley is an HTTP library that makes networking for Android apps easier and, most importantly, faster.

GitHub 🌟：3k

项目参考Blog：[Android Volley使用（一）Volley的基本用法](https://blog.csdn.net/u010356768/article/details/87720280)

项目引入

```
    dependencies {
        ...
        implementation 'com.android.volley:volley:1.2.0'
    }
```

#### [Java-WebSocket](https://github.com/TooTallNate/Java-WebSocket)

项目简介：A barebones WebSocket client and server implementation written in 100% Java.

GitHub 🌟：7.9k

项目参考Blog：[java WebSocket开发入门WebSocket](https://www.jianshu.com/p/d79bf8174196)

项目引入

```
    dependencies {
        ...
        implementation 'org.java-websocket:Java-WebSocket:1.5.1'
    }
```

### 文件下载

#### [FileDownloader](https://github.com/lingochamp/FileDownloader)

项目简介：Android 文件下载引擎，稳定、高效、灵活、简单易用

GitHub 🌟：10.1k

项目参考Blog：[FileDownloader](https://github.com/lingochamp/FileDownloader/blob/master/README-zh.md)

项目引入

```
    dependencies {
        ...
        implementation 'com.liulishuo.filedownloader:library:1.7.7'
    }
```

#### [okdownload](https://github.com/lingochamp/okdownload)

项目简介：可靠，灵活，高性能以及强大的下载引擎。

GitHub 🌟：4.2k

项目参考Blog：[Simple Use Guideline](https://github.com/lingochamp/okdownload/wiki/Simple-Use-Guideline)

项目引入

```
    dependencies {
        ...
        // core
		com.liulishuo.okdownload:okdownload:{latest_version}
		// provide sqlite to store breakpoints
		com.liulishuo.okdownload:sqlite:{latest_version}
		// provide okhttp to connect to backend
		// and then please import okhttp dependencies by yourself
		com.liulishuo.okdownload:okhttp:{latest_version}
		// provide interface to match filedownloader
		com.liulishuo.okdownload:filedownloader:{latest_version}
		// provide interface for kotlin extension
		com.liulishuo.okdownload:ktx{latest_version}
    }
```

#### [PRDownloader](https://github.com/MindorksOpenSource/PRDownloader)

项目简介：A file downloader library for Android with pause and resume support

GitHub 🌟：2.8k

项目参考Blog：[安卓文件下载库 | PRDownloader](https://www.jianshu.com/p/3cf8b31f3a11)

项目引入

```
    dependencies {
        ...
        implementation 'com.mindorks.android:prdownloader:0.6.0'
    }
```

## 存储

#### [MMKV](https://github.com/Tencent/MMKV)

项目简介：MMKV 是基于 mmap 内存映射的 key-value 组件，底层序列化/反序列化使用 protobuf 实现，性能高，稳定性强，可以替代SharedPreferences

GitHub 🌟：12.4k

项目参考Blog：[MMKV——1.使用](https://www.jianshu.com/p/bc6d8b714635)、[MMKV——2.原理](https://www.jianshu.com/p/83ee82c30e53)

项目引入

```
       implementation 'com.tencent:mmkv-static:1.2.7'
       // replace "1.2.7" with any available version
```

## 优化

#### [leakcanary](https://github.com/square/leakcanary)

项目简介：A memory leak detection library for Android

GitHub 🌟：25.9k

项目参考Blog：[LeakCanary官网](https://square.github.io/leakcanary/)

项目引入

```
      // debugImplementation because LeakCanary should only run in debug builds.
      debugImplementation 'com.squareup.leakcanary:leakcanary-android:2.7'
```

## 日志

#### [logger](https://github.com/orhanobut/logger)

项目简介：Simple, pretty and powerful logger for android

GitHub 🌟：12.1k

项目参考Blog：[Android 日志记录杂谈-Logger,Timber,logback-android](https://www.jianshu.com/p/39834be3cb6c)

项目引入

```
  implementation 'com.orhanobut:logger:2.2.0'
```

#### [timber](https://github.com/JakeWharton/timber)

项目简介：A logger with a small, extensible API which provides utility on top of Android's normal Log class.

GitHub 🌟：8.8k

项目参考Blog：1.[Timber: Android日志记录](https://www.jianshu.com/p/4f54fcba3ad3) 2.[Android 日志记录杂谈-Logger,Timber,logback-android](https://www.jianshu.com/p/39834be3cb6c)

项目引入

```
  implementation 'com.jakewharton.timber:timber:4.7.1'
```

## 权限

#### [PermissionX](https://github.com/guolindev/PermissionX)

项目简介：PermissionX is an extension Android library that makes Android runtime permission request extremely easy

GitHub 🌟：1.6k

项目参考Blog：[PermissionX-作者:guolin](https://blog.csdn.net/guolin_blog/category_10108528.html)

项目引入

```
  implementation 'com.permissionx.guolindev:permissionx:1.4.0'
```

## 不再推荐

以下条目是因**GitHub更新时间过久**、**已停止维护**、**有更好替代品**等原因被推荐替换的项目

**GitHub更新时间过久**：GitHub上次更新时间过久，作者可能已经放弃维护，使用时可能会产生BUG，请谨慎考虑使用

**已停止维护**：作者已明确声明项目停止维护，不再提供功能更新、BUG修复，不推荐使用此类项目

**有更好替代品**：此类项目仍然推荐使用，但有更好的开源框架或者官方库可以替代

条目详细格式如下：

```
框架/组件           //框架或组件的Github地址，点击查看
GitHub 🌟：        //GitHub star星数
GitHub更新时间      //GitHub上次更新时间
Releases最新版本：  //GitHub上最新的Releases版本
不再推荐原因：         //因某种原因，推荐使用其它框架或组件替换
替代框架：          //推荐使用的替代框架或组件
```

###  ~~[AndroidEventBus](https://github.com/hehonghui/AndroidEventBus)~~

GitHub 🌟：1.6k

GitHub更新时间：2018年3月

Releases最新版本：2015年5月 Version-1.0.4

不推荐原因：已停止维护[DEPRECATED] 

替代框架：无

###  ~~[BadgeView](https://github.com/qstumn/BadgeView)~~

GitHub 🌟：3.9k

GitHub更新时间：2017年4月

Releases最新版本：2017年9月 Version-1.1.3

不推荐原因：已停止维护[DEPRECATED]

替代框架：无

### ~~[ButterKnife](https://github.com/JakeWharton/butterknife)~~

GitHub 🌟：25.7k

GitHub更新时间：2020年9月

Releases最新版本：2020年8月 Version-10.2.3

不推荐原因：已停止维护[DEPRECATED] 

替代框架：官方JetPack库的[DataBinding](https://developer.android.google.cn/jetpack/androidx/releases/databinding?hl=zh-cn)、官方的[ViewBinding](https://developer.android.google.cn/topic/libraries/view-binding?hl=zh-cn)

###  ~~[CardSwipeLayout](https://github.com/yuqirong/CardSwipeLayout)~~

GitHub 🌟：1.1k

GitHub更新时间：2017年3月

Releases最新版本：无Release版本

不推荐原因：GitHub更新时间过久

替代框架：无

### ~~[greenDAO](https://github.com/greenrobot/greenDAO)~~

GitHub 🌟：12.4k

GitHub更新时间：2021年2月

Releases最新版本：2020年5月 Version-3.3.0

不推荐原因：使用比较复杂，有更好替代品

替代框架：官方JetPack库的[Room](https://developer.android.google.cn/jetpack/androidx/releases/room?hl=zh-cn)、郭霖大神的[LitPal](https://github.com/guolindev/LitePal)

### ~~[MVPArms](https://github.com/JessYanCoding/MVPArms/wiki#1)~~

GitHub 🌟：10k

GitHub更新时间：2020年6月

Releases最新版本：2019年7月 Version-2.5.2

不推荐原因：有更好的替代品

替代框架：官方推荐的MVVM架构，配合JetPack可以很轻松搭建MVVM架构，使用[官方JetPack库](https://developer.android.google.cn/jetpack?hl=zh-cn)搭建MVVM架构

###  ~~[NineOldAndroids](https://github.com/JakeWharton/NineOldAndroids)~~

GitHub 🌟：4.5k

GitHub更新时间：2014年10月

Releases最新版本：2012年6月 Version-2.4.0

不推荐原因：已停止维护[DEPRECATED] 

替代框架：无

###  ~~[NumberProgressBar](https://github.com/daimajia/NumberProgressBar)~~

GitHub 🌟：5.9k

GitHub更新时间：2017年7月

Releases最新版本：2014年8月 Version-1.2

不推荐原因：GitHub更新时间过久

替代框架：无

###  ~~[picasso](https://github.com/square/picasso)~~

GitHub 🌟：17.9k

GitHub更新时间：2020年9月

Releases最新版本：2020年8月 Version-2.8

不推荐原因：有更好的替代品

替代框架：[Glide](https://github.com/bumptech/glide)

###  ~~[ViewPagerIndicator](https://github.com/LinweiJ/ViewPagerIndicator)~~

GitHub 🌟：368

GitHub更新时间：2019年8月

Releases最新版本：2019年8月 Version-0.3.0

不推荐原因：有更好的替代品

替代框架：[MagicIndicator](https://github.com/hackware1993/MagicIndicator)https://github.com/hackware1993/MagicIndicator)

### ~~[Matisse](https://github.com/zhihu/Matisse)~~

GitHub 🌟：11.9

GitHub更新时间：2019年10月

Releases最新版本：2019年8月 Version-0.3.0

不推荐原因：已停止维护[DEPRECATED]

替代框架：[PictureSelector](https://github.com/LuckSiege/PictureSelector)



