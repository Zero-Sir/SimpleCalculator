# 微信小程序-SimpleCalculator
微信小程序版简易计算器，可用于微信小程序入门练手

## 效果图
| 计算主界面 | 历史计算界面 |
|-------------|-------------|
| ![](./preview/preview1.png) | ![](./preview/preview2.png) |

## 相关
 1.微信小程序页面布局<br>
    CSS Flexbox布局， 比例布局（适应各个尺寸手机）<br>
 2.微信小程序时间使用<br>
    按钮事件绑定、页面跳转等<br>
 3.Page用于占据整版手机屏幕<br>
 4.wxml、wxsss、js、json文件使用方法<br>
 5.基本组件：view、text、icon、button组件的使用<br>
 6.修改导航栏navigate（在app.json）<br>
 7.wx.setStorageSync(), wx.getStorageSync():存储全局数据
 
 ## 可能存在的问题
 1.没有进行较为全面的测试，可能存在小bug<br>
 2.由于只是简单的demo，没有用到（），所以只用了简单的逻辑处理运算，没有用更严谨有效的算术式计算方法，所以只能进行单个运算，不能进行一连串运算
 3.%运算不是百分数，而是取余<br>
