# titleview-master

Android自定义标题栏，根据不同需求统一定制标题栏，避免重复在xml中设置标题栏样式<br>

效果图:<br>
![image](https://github.com/JarekWang/titleview-master/blob/master/app/screenshot/screen_shot.png)
<br>
<br>
<br>
## 使用方式：<br>

```java
<com.jarek.title.view.TitleView
        android:id="@+id/title_main"
        android:layout_width="match_parent"
        android:background="#0093fe"
        title:title_name="标题"
        title:right_text="@string/more"
        title:title_text_color="@android:color/white"
        title:right_image_two="@mipmap/icon_crop_rotate"
        title:title_text_size="20sp"
        title:small_text_size="15sp"
        title:left_text="返回"
        title:left_text_drawable_left="@mipmap/back_normal"
        title:right_text_drawable_right="@mipmap/bar_button_right"
        android:layout_height="50dp"/>
```
<br>
[我的博客](http://www.cnblogs.com/jarek/)