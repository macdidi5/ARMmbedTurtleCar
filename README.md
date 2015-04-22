# ARM mbed藍牙遙控車

示範影片：

* 2015/04/22：https://youtu.be/otHd1h4B4kU

## 這台貼滿膏藥的車子

開始接觸ARM mbed以後...

* 老婆：可不可以做一台遙控車啊？
* 我：當然可以，不過...

過了一陣子以後：

* 老婆：它可以用藍牙喔！那可不可做作一台藍牙遙控車啊？
* 我：是可以啦，不過...

又過了一陣子以後：

* 老婆：如果有一台藍牙遙控車一定很好玩...
* 我：...

所以就有了這台貼滿膏藥的藍牙遙控車。

## 歷程

* 2015/04/22。公開原始程式碼與線路圖。

## 零件列表

* Freescale FRDM-KL25Z，ARM mbed開發板
* 麵包板
* 一些杜邦線
* 一些電阻
* HC-05，藍牙模組
* HC-SR04，超音波測距感應模組
* L293D，直流馬達控制晶片
* 直流馬達、6V，兩個
* 齒輪組，兩個
* 輪子，兩個
* 樂高底板
* 行動電源
* 塑膠板
* 膠帶

## 線路圖

* HC-05，藍牙模組

![](https://github.com/macdidi5/ARMmbedTurtleCar/blob/master/images/HC05.png)

* HC-SR04，超音波測距感應模組

![](https://github.com/macdidi5/ARMmbedTurtleCar/blob/master/images/HCSR04.png)

* L293D，直流馬達控制晶片

![](https://github.com/macdidi5/ARMmbedTurtleCar/blob/master/images/L293D.png)

## ARM mbed 應用程式

原始程式碼公開在 ARM mbed 開發平台：

<a href="http://developer.mbed.org/users/macdidi5/code/mbedTurtleCar/">http://developer.mbed.org/users/macdidi5/code/mbedTurtleCar/</a>

## Android App

Android Studio專案，原始程式碼專案目錄「TurtleCarMobile」。
