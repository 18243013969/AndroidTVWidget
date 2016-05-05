# Android TV 开发框架

官方论坛：http://www.androidtvdev.com/ 
QQ群：522186932

## 整体目录结构
![输入图片说明](http://git.oschina.net/uploads/images/2016/0505/155301_21a6621f_111902.png "在这里输入图片标题")
*AndroidTvWidet 目录是TV开发框架的 库文件.
*demo 目录是 例子.
*doc 目录是存放文档的.
*other_libs 目录是 AndroidTvWidget开发框架 依赖的一些库文件.
*Tool 目录 是 屏幕像素转换工具.

## AndroidTVwidget库目录结构

![框架目录结构](http://git.oschina.net/uploads/images/2016/0505/155151_939fc32a_111902.png "在这里输入图片标题")

com.open.androidtvwidget.adapter : 标题栏的adapter基类.
com.open......bridge : MainUpView的依赖类，比如移动的动画都在这里实现的
com.open.....cache: 缓存
com.open....keyboard: 键盘
com.open....menu : 菜单
com.open.android...recycle : recyclerview 的支持（gridview)
com.open.android...utils:一些常用函数封装
com.open...android..view:一些TV改造的控件.(下面我们将接受这里面的控件使用方法)

API文档：

    https://git.oschina.net/hailongqiu/AndroidTVWidget/attach_files

使用说明: 

   https://git.oschina.net/hailongqiu/AndroidTVWidget/wikis/AndroidTVWidget-use-manual

键盘使用说明:
   
   https://git.oschina.net/hailongqiu/AndroidTVWidget/wikis/Android-TV-%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8%E9%94%AE%E7%9B%98%E6%8E%A7%E4%BB%B6%28SkbContainer%29

项目导入说明:
   
   https://git.oschina.net/hailongqiu/AndroidTVWidget/wikis/AndroidTVWidget-use-manual%28Android-Studio%29

   https://git.oschina.net/hailongqiu/AndroidTVWidget/wikis/AndroidTVWidget-use-manual%28Eclipse%E5%AF%BC%E5%85%A5%29


 欢迎进入 TV开发，希望大家不断的分享代码，一起进步，谢谢. （hailongqiu 356752238@qq.com）

欢迎加入QQ群，一起学习，一起进步，这里有很多TV方面的高手噢。
  
![输入图片说明](http://git.oschina.net/uploads/images/2016/0223/094451_e49419a7_111902.png "在这里输入图片标题")
 

天天加班加点，欢迎支持(用于网站论坛维护)

![天天加班加点，欢迎支持](http://git.oschina.net/uploads/images/2016/0310/133650_1cc016cc_111902.png "天天加班加点，欢迎支持")


##Tab 测试DEMO图片.
    
![输入图片说明](http://git.oschina.net/uploads/images/2016/0406/110716_e9f61513_111902.png "在这里输入图片标题")

![输入图片说明](http://git.oschina.net/uploads/images/2016/0406/110827_505fcc9c_111902.png "在这里输入图片标题")

![GridViewTV](http://git.oschina.net/uploads/images/2016/0428/112433_94b26833_111902.png "在这里输入图片标题")

![输入图片说明](http://git.oschina.net/uploads/images/2016/0406/110937_f5e73cf4_111902.png "在这里输入图片标题")

[ViewPager-DEMO]

![输入图片说明](http://git.oschina.net/uploads/images/2016/0406/111118_325845c8_111902.png "在这里输入图片标题")

[键盘-DEMO]

![输入图片说明](http://git.oschina.net/uploads/images/2016/0406/111129_38af8a29_111902.png "在这里输入图片标题")

![输入图片说明](http://git.oschina.net/uploads/images/2016/0422/204409_fc65ce11_111902.png "在这里输入图片标题")

## 后期加入
   
   网络加载布局

   
## 感谢开源[参考代码]
<p>
<a href="https://github.com/XiaoMi/android_tv_metro">XiaoMi android_tv_metro </a>
</p>
<p>
<a href="https://github.com/lf8289/BorderViewDemo">BorderViewDemo</a>
</p>


## 版本更新

v1.4.0 

*添加recyclerview的支持

*修复gridviewTv 更新数据崩溃

*修改GridViewTV demo

*修复键盘DEMO 崩溃

*倒影控件添加间距接口

*整理移动动画的函数