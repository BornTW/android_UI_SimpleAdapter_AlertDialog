# android_UI_SimpleAdapter_AlertDialog
### 一、SimpleAdapter简介
SimpleAdapter,跟名字一样,一个简单的适配器,既为简单,就只是被设计来做简单的应用的,比如静态数据的绑定,不过仍然有自定义的空间,
比如说在每一个ListItem中加一个按钮并添加响应事件

### 利用SimpleAdapter实现如下界面效果
（1）注意列表项的布局
（2）图片使用QQ群附件资源
（3）使用Toast显示选中的列表项信息
![SimpleAdapter效果图片](https://github.com/BornTW/android_UI_SimpleAdapter_AlertDialog/blob/master/Images/android_UI_SimpleAdapter_AlertDialog_1.jpg)


### 二、AlertDialog简介
首先，我们来了解一下AlertDialog的大体创建顺序。与TextView、Button这些控件稍有不同，AlertDialog并不是初始化（findViewById）之后就直接调用各种方法了。仔细想想AlertDialog的使用场景， 它并不像TextView和Button那些控件似的一般都是固定在界面上，而是在某个时机才会触发出来（比如用户点击了某个按钮或者断网了）。所以AlertDialog并不需要到布局文件中创建，而是在代码中通过构造器（AlertDialog.Builder）来构造标题、图标和按钮等内容的。

（1）创建构造器AlertDialog.Builder的对象；<br>
（2）通过构造器的对象调用setTitle、setMessage等方法构造对话框的标题、信息和图标等内容；<br>
（3）根据需要，设置正面按钮、负面按钮和中立按钮；<br>
（4）调用create方法创建AlertDialog的对象；<br>





