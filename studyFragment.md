# Android Native

## 第一行代码4,9,12的快速复习(✅)

- **Progressbar的scrollbarStyle属性**

![scrollbarStyle类别](https://cdn.jsdelivr.net/gh/foolscientist/PersonalPictureBed@main/img/202112221814584.png)

​	其中一共有四种类型，为2x2，inside/outside表明当前的progressBar是否在当前的内容的view之内，overlay/inset则表明当前的这个bar是否会新开辟一个空间来进行特殊的表示。具体说明https://stackoverflow.com/questions/3103132/android-listview-scrollbarstyle。

## Bitmap全方位学习(✅)

- [Android Bitmap（位图）详解](https://www.cnblogs.com/shakinghead/p/11025805.html)

- [Android入门——Bitmap和BitmapFactory ](https://www.cnblogs.com/Free-Thinker/p/6394797.html)
- [Android中View转换为Bitmap](https://blog.csdn.net/rj_jqd/article/details/8601584?utm_medium=distribute.pc_relevant.none-task-blog-2~default~baidujs_baidulandingword~default-0.no_search_link&spm=1001.2101.3001.4242.1&utm_relevant_index=3)

- https://blog.csdn.net/cquwentao/article/details/51445269?utm_medium=distribute.pc_relevant.none-task-blog-2~default~baidujs_baidulandingword~default-1.queryctr&spm=1001.2101.3001.4242.2&utm_relevant_index=4)

## 自定义View

- 这位爷的专栏https://blog.csdn.net/cquwentao
- [Android动态添加View](https://blog.csdn.net/zhangzhilai8/article/details/47263605)

## Path

- [Android开发之Path详解](https://blog.csdn.net/xiangzhihong8/article/details/78278931/)

## Rect & RectF

## Android动效

## Android手势

- 

## Canvas、Paint、draw、Drawable

- Paint防止锯齿

  ```java
  paint.setAntiAlias(true);
  ```

## UI基础+实战B站视频

- **网址：**https://www.bilibili.com/video/BV16B4y1w7ZG?from=search&seid=10296294438983947710&spm_id_from=333.337.0.0

## SpannableString

## ViewModel

**具体的讲解** https://zhuanlan.zhihu.com/p/76361500


## XML文件当中的Selector标签

## Kotlin ?:（复合符号）

https://blog.csdn.net/lckj686/article/details/80448471

## ActionBar

https://www.jianshu.com/p/81d0bcb282cb

## LiveData

## View.postInvalidate()

## 工厂模式

## **FileDescriptor** 

## ConstraintLayout

- **学习资料：**
  - 第一行代码公众号：约束布局

## Android动态添加View

https://blog.csdn.net/zhangzhilai8/article/details/47263605

## InputStream



# Kotlin

## Kotlin Map

https://www.jianshu.com/p/9dd5ddf0133a

## Kotlin CopyOnWriteArrayList



# Flutter



# 数据结构

# LinkedHashMap(LRU的策略实现，二级缓存，多级缓存)

# 系统架构：

## 基础图片库等内容的架构思想

1. 建立ImageLoader接口，定义对应的方法内容
2. 建立ImageLoaderImpl类，实现对应的方法（可以使用Fresco，Glide等方法来实现）
3. 建立对象实例池，业务方通过ImageLoader.getInstance获取对应的对象实例
4. 使用对应的具体实例，进行真正的图片加载
