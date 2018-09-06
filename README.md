# Douban-dome
## 豆瓣市集（移动端）-demo<br>
### 主要页面：<br>
主页：https://github.com/WangYingYaTou/Douban-dome/blob/master/img/home.png <br>
     https://github.com/WangYingYaTou/Douban-dome/blob/master/img/home1.png<br>
详情：https://github.com/WangYingYaTou/Douban-dome/blob/master/img/detail.png<br>
登录：https://github.com/WangYingYaTou/Douban-dome/blob/master/img/login.png<br>
其他方式登录：https://github.com/WangYingYaTou/Douban-dome/blob/master/img/login-other.png<br>
注册:https://github.com/WangYingYaTou/Douban-dome/blob/master/img/register.png<br>
购物车：https://github.com/WangYingYaTou/Douban-dome/blob/master/img/shoppingcart.png<br>
收货地址：https://github.com/WangYingYaTou/Douban-dome/blob/master/img/address.png<br>
## 移动端屏幕的适配
  　<meta name="viewport" content="width=device-width"><br>
    meta viewport 中有6个通用属性：<br>
      <br>width 设置layout viewport的宽度 正整数或字符串 'width-device'<br>
      initial-scale 设置页面的初始缩放值，数字或小数<br>
      minimum-scale 允许用户的最小缩放值 数字或小数<br>
      maximum-scale 允许用户的最大缩放值 数字或小数<br>
      height 设置layout viewport 的高度，这个属性很少用到<br>
      user-scaleabel 是否允许用户进行缩放 'no'或‘yes’ 还有2个需要特别注意的两个属性<br>
      target-densitydpi 在andriod 4.0一下的设备中，不支持设置viewport的width，android 自带浏览器支持设置 target-densitydpi来达到目的；<br>
      miniual-ui ios的safari为meta表天新增的属性，在网页加载是隐藏顶部的地址栏和底部的导航栏<br>
  ## css部分
     rem/em
     <br> rem 单位，他们转化为像素大小取决于页根元素的字体大小，即 html 元素的字体大小。 根元素字体大小乘以你 rem 值。<br>
          em单位时，像素值将是em值乘以使用em单位的元素的字体大小。<br>
