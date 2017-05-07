# runtime
使用runtime运行时刻一句代码获取苹果官方私有属性,私有属性的默认值,及私有方法.

项目使用步骤 :

1.将demo中 NSObject+SAMRuntime.h/NSObject+SAMRuntime.m 分类直接拖到需要使用的项目中.

2.在ViewController.m中,将需要获取其信息的类,设置为对象属性,用对象属性,调取分类中的三个方法.

3.打印输出结果.

4.使用得到的私有属性及信息,做相应的事.

项目结果演示 :

例如 :系统UIDatePicker类中,设置文字颜色的属性为私有属性,通过上面方法,得到结果如下:

只能设置为黑色,无阴影.

![image](https://github.com/samcydia/runtime/blob/master/描述图片/Snip20170507_4.png)

获取到的私有属性

![image](https://github.com/samcydia/runtime/blob/master/描述图片/Snip20170507_5.png)

获取到的私有属性默认值及方法参数信息

![image](https://github.com/samcydia/runtime/blob/master/描述图片/Snip20170507_6.png)

获取后重新设置

![image](https://github.com/samcydia/runtime/blob/master/描述图片/Snip20170507_7.png)
