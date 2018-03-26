# OCTabBarDemo

# PDFPageDemo

![](https://img.shields.io/badge/platform-iOS-red.svg) ![](https://img.shields.io/badge/language-Objective--C-blue.svg) ![](https://img.shields.io/badge/download-9.9MB-yellow.svg) ![](https://img.shields.io/badge/license-MIT%20License-brightgreen.svg)

[EN](#Requirements) | [中文](#中文说明)

## 🤖 Requirements

* iOS 9.0+
* Xcode 9.0+
* Objective-C

## 🚀 Getting started

## 🎨 Why test the UI?

|1.Show Page |2.Show Page |3.Show Page |
| ------------- | ------------- | ------------- |
| ![](http://og1yl0w9z.bkt.clouddn.com/18-3-26/70011349.jpg) | ![](http://og1yl0w9z.bkt.clouddn.com/18-3-26/6411440.jpg) | ![](http://og1yl0w9z.bkt.clouddn.com/18-3-26/98018306.jpg) | 
| Home Jump Button | Jump Page | Other Page |

## 🛠 Used

### Core code

```OC
/**
 tabBar click event callback
 
 @param tabBar tabBar
 @param viewController selected viewController
 */
-(void)CustomTabBar:(CustomTabBar *)tabBar didSelectViewController:(UIViewController *)viewController;

/**
 * Initialization
 *
 * @param controllerArray array of controllers
 * @param titleArray header array
 * @param imageArray picture array
 * @param selImageArray selected image array
 * @param height tabBar height (pass nil or <49.0 are treated as 49.0))
 *
 * @return self
 */
- (instancetype)initWithControllerArray:(NSArray *)controllerArray titleArray:(NSArray *)titleArray imageArray:(NSArray *)imageArray selImageArray:(NSArray *)selImageArray height:(CGFloat)height;

/*
 Hide the TabBar call system method
 VC.hidesBottomBarWhenPushed = YES;
 */

/**
 * Set tabBar to display the specified controller
 *
 * @param index location
 */
-(void)showControllerIndex:(NSInteger)index;

/**
 * Digital marker
 *
 * @param badge to display the number
 * @param index location
 */
-(void)showBadgeMark:(NSInteger)badge index:(NSInteger)index;

/**
 * Little red dot
 *
 * @param index location
 */
-(void)showPointMarkIndex:(NSInteger)index;

/**
 * Hide specified location marker
 *
 * @param index location
 */
-(void)hideMarkIndex:(NSInteger)index;
```


## 📝 App Submission

## ⚖ License

```
MIT License

Copyright (c) 2017 ReverseScale

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 😬 Contributions

* WeChat : WhatsXie
* Email : ReverseScale@iCloud.com
* Blog : https://reversescale.github.io

-------

#中文说明
------

![](https://img.shields.io/badge/platform-iOS-red.svg) ![](https://img.shields.io/badge/language-Objective--C-blue.svg) ![](https://img.shields.io/badge/download-9.9MB-yellow.svg) ![](https://img.shields.io/badge/license-MIT%20License-brightgreen.svg)

## 🤖 要求

* iOS 9.0+
* Xcode 9.0+
* Objective-C

## 🚀 准备开始

## 🎨 测试 UI 什么样子？

|1.展示页 |2.展示页 |3.展示页 |
| ------------- | ------------- | ------------- | 
| ![](http://og1yl0w9z.bkt.clouddn.com/18-3-26/70011349.jpg) | ![](http://og1yl0w9z.bkt.clouddn.com/18-3-26/6411440.jpg) | ![](http://og1yl0w9z.bkt.clouddn.com/18-3-26/98018306.jpg) | 
| 首页跳转按钮 | 跳转页面 | 其他页面 | 

## 🛠 使用

### 核心代码
```OC
/**
 tabBar 点击事件回调
 
 @param tabBar   tabBar
 @param viewController 选中的viewController
 */
-(void)CustomTabBar:(CustomTabBar *)tabBar didSelectViewController:(UIViewController *)viewController;

/**
 *  初始化
 *
 *  @param controllerArray 控制器数组
 *  @param titleArray      标题数组
 *  @param imageArray      图片数组
 *  @param selImageArray   选中图片数组
 *  @param height          tabBar 高度(传nil或<49.0均按49.0处理))
 *
 *  @return self
 */
- (instancetype)initWithControllerArray:(NSArray *)controllerArray titleArray:(NSArray *)titleArray imageArray:(NSArray *)imageArray selImageArray:(NSArray *)selImageArray height:(CGFloat )height;

/*
 隐藏 TabBar 调用系统方法
 VC.hidesBottomBarWhenPushed = YES;
 */

/**
 *  设置tabBar显示指定控制器
 *
 *  @param index 位置
 */
-(void)showControllerIndex:(NSInteger)index;

/**
 *  数字角标
 *
 *  @param badge 所要显示数字
 *  @param index 位置
 */
-(void)showBadgeMark:(NSInteger)badge index:(NSInteger)index;

/**
 *  小红点
 *
 *  @param index 位置
 */
-(void)showPointMarkIndex:(NSInteger)index;

/**
 *  隐藏指定位置角标
 *
 *  @param index 位置
 */
-(void)hideMarkIndex:(NSInteger)index;
```

## ⚖ 协议

```
MIT License

Copyright (c) 2017 ReverseScale

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 😬  联系

* 微信 : WhatsXie
* 邮件 : ReverseScale@iCloud.com
* 博客 : https://reversescale.github.io
