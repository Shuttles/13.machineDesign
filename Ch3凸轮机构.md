通过前几章的学习，我们知道低副机构一般只能近似地实现给定运动规律，并且设计复杂。本章将学习另外一种不同的机构--凸轮机构。



# 1.凸轮机构类型及应用

1. 凸轮机构主要有***<u>凸轮</u>***、***<u>从动件</u>***和***<u>机架</u>***三部分组成。

## 具体定义

![img](https://wx1.sinaimg.cn/mw690/005LasY6gy1gd1d2ub9iwj30pk0fdwhy.jpg)



### 适用场合

广泛用于各种机械，特别是自动机械、自动控制装置和装配生产线



### 凸轮机构的优点

结构简单、紧凑、工作可靠，可以使从动件准确实现各种预期的运动规律，还易于实现多个运动的相互协调配合。



### 缺点

凸轮轮廓与从动件之间是高副接触，易于磨损。



## 作用

实现从动件往复运动或摆动***<u>任意运动规律</u>***。

## 分类

![img](https://wx2.sinaimg.cn/mw690/005LasY6gy1gd1d8jpc3vj30sa0iajv1.jpg)

![img](https://wx2.sinaimg.cn/mw690/005LasY6gy1gd1d8qpcs8j30s50g8q5s.jpg)

![img](https://wx1.sinaimg.cn/mw690/005LasY6gy1gd1d92sfxhj30s30iiq5w.jpg)



## 凸轮名词术语及符号

![](https://wx3.sinaimg.cn/mw690/005LasY6gy1gd1db3leroj30s10hggq1.jpg)

+ ***<u>基圆半径就是凸轮廓线上与旋转中心距离最小的那段距离</u>***！！！
+ ***<u>所以起始点就是S = 0那点即最低点</u>***！！

+ 远休和近休的时候从动件S不变--因为凸轮轮廓那是段圆弧！！

![img](https://wx4.sinaimg.cn/mw690/005LasY6gy1gd1dj2m8mej30s10i4q60.jpg)

偏距圆的特征：

***<u>从动杆运动过程中始终与偏距圆相切</u>***！！！！

![img](https://wx3.sinaimg.cn/mw690/005LasY6gy1gd1dm1is1dj30hu0dkwke.jpg)





# 2.从动件的运动规律及凸轮机构的压力角

## 从动件的运动规律



![img](https://wx3.sinaimg.cn/mw690/005LasY6gy1gd1ebtye4qj30rg0frjtt.jpg)

![img](https://wx2.sinaimg.cn/mw690/005LasY6gy1gd1edjx4rpj30ri0hp777.jpg)

![img](https://wx2.sinaimg.cn/mw690/005LasY6gy1gd1eenz6bfj30sa0id77r.jpg)

![img](https://wx4.sinaimg.cn/mw690/005LasY6gy1gd1efsxxlaj30tp0lc0yc.jpg)

![img](https://wx4.sinaimg.cn/mw690/005LasY6gy1gd1eh2chlej30rw0j5jve.jpg)

![img](https://wx4.sinaimg.cn/mw690/005LasY6gy1gd1ehz7ohdj30sf0i8adv.jpg)



## 凸轮机构的压力角

![img](https://wx4.sinaimg.cn/mw690/005LasY6gy1gd1elt8hvtj30ru0hstbq.jpg)

***<u>压力角是接触点公法线方向(受力方向)与速度方向所夹锐角</u>***！！

回程的时候承受压力较小，所以许用压力角可以大一些！！



### 压力角α与基圆半径r

![img](https://wx4.sinaimg.cn/mw690/005LasY6gy1gd1epj2kftj30s30hlado.jpg)

![img](https://wx2.sinaimg.cn/mw690/005LasY6gy1gd1es68ebuj30s80lcgqx.jpg)

PS：凸轮逆时针转动，从动杆适当右偏置，这样减小了推程压力角，但也同时增大了回程压力角。

这样可以有利于传动

顺时针则相反！





# 3.图解法设计凸轮轮廓

## 原理

设计图轮廓线是采用反转法原理，即当尖底从动件凸轮机构以等角速度Ω顺时针转动时，从动件按预期运动规律运动。

```c
//这是教材上的一段话，我没看懂
/*
现设想给该凸轮机构加一个等角速度Ω逆时针转动时，显然凸轮机构中运动关系没变，但是根据运动合成，凸轮将静止不动，这时，尖底运动的轨迹就是凸轮轮廓曲线。
*/
```

下面是ppt上的一段话

***<u>可假设凸轮静止不动，而使推杆相对于凸轮作反转运动；同时又在其导轨内作预期运动，作出推杆在这种复合运动中的一系列位置，则其尖顶的轨迹就是所要求的的凸轮廓线。</u>***



## 具体做法

![img](https://wx3.sinaimg.cn/mw690/005LasY6gy1gd3phmh3exj30r40i611l.jpg)

![img](https://wx2.sinaimg.cn/mw690/005LasY6gy1gd3podxwxuj30so0l07f9.jpg)







# 4.此章习题(会考大题)

## 套路

1. 一定要确定==旋转中心==！！然后想象它的旋转过程！想象不出来就用纸模拟！
2. 先找==起始点==(向径最小的点)，画出基圆



## 偏心机构结论

1. 升程h就是==向径最大的点到旋转中心的距离==`-` 向径最小的点(起始点)到旋转中心的距离

   因此求升程h就是找出向径最小、最大的点！！







![img](https://wx4.sinaimg.cn/mw690/005LasY6gy1gd4wnnswi4j30r90id0we.jpg)

<u>***这一题我花了很久才弄懂，一开始老师讲我都是很懵的，最后是通过我自己剪了个凸轮，在纸上模拟旋转过程才弄懂的！***</u>

1. 这题就是按套路来，做完套路1、2之后就有了思路，就能知道起始点位置和最高点位置，再画出来，根据几何关系求解就可以求得最大位移h了。
   + 实际上，如果指定了x轴为现在的这条水平直径，***<u>那么杆的高度就是O点、接触点、A点所组成的直角三角形的一条直角边</u>***，并且O点到接触点的距离为斜边，另一条直角边恒定，为e
   + 根据这个，就可以画出各位置的高度了
   + ==可以思考出，o点到接触点的距离(直角三角形的斜边)越大，杆的高度越大；距离越小，杆的高度越小。因此就可得出最高点(***<u>也就是向径最大的点</u>***)==

![img](https://wx4.sinaimg.cn/mw690/005LasY6gy1gd52t0ifomj30g50ehq9s.jpg)

2. 既然知道了最低位置(起始点)和最高位置，那么推程角就很好求了

   ![img](https://wx3.sinaimg.cn/mw690/005LasY6gy1gd52vwjcanj30fp0hlajj.jpg)

   