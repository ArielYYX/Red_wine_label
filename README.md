# Red_wine_label
1.基于Opencv库实现对红酒酒标的匹配，掌握了图像的SIFT特征提取; 2.熟悉hdf5库的分类的机制; 3.利用边缘检测确定酒标的区域并建立黑白模板; 4.利用Ransac算法对图像特征点匹配对提纯，降低图像旋转，尺寸缩放，图像平移，光照的变化的影响。 5.Qt 程序编写提取汽车模型的黑白模板，和Ransac算法匹配结果演示。

基于Opencv库实现红酒酒标的识别
===================================  
### 酒标图片  （酒标图片库>100000张）
不一一列举


### 酒标边缘Mask图片
![github](https://github.com/df865017/Red_wine_label/blob/master/pic/wine_label/mask/image004.jpg "github") </br>
![github](https://github.com/df865017/Red_wine_label/blob/master/pic/wine_label/mask/image013.jpg "github") </br>
![github](https://github.com/df865017/Red_wine_label/blob/master/pic/wine_label/mask/image021.jpg "github") </br>
![github](https://github.com/df865017/Red_wine_label/blob/master/pic/wine_label/mask/image021.jpg "github") </br>
![github](https://github.com/df865017/Red_wine_label/blob/master/pic/wine_label/mask/image029.jpg "github") 

### 结果排名前5图片
![github](https://github.com/df865017/Red_wine_label/blob/master/pic/wine_label/result/image013.jpgimage007.jpg "github") </br>
![github](https://github.com/df865017/Red_wine_label/blob/master/pic/wine_label/result/image013.jpgimage009.jpg "github") </br>
![github](https://github.com/df865017/Red_wine_label/blob/master/pic/wine_label/result/image013.jpgimage013.jpg "github") </br>
![github](https://github.com/df865017/Red_wine_label/blob/master/pic/wine_label/result/image013.jpgimage015.jpg "github") </br>
![github](https://github.com/df865017/Red_wine_label/blob/master/pic/wine_label/result/image013.jpgimage019.jpg "github") 


Qt C++编写的Ransac特征匹配对提纯
===================================  
### 处理前
![github](https://github.com/df865017/Red_wine_label/blob/master/pic/qt_ransac/src/mountain1.JPG "github") 
![github](https://github.com/df865017/Red_wine_label/blob/master/pic/qt_ransac/src/mountain2.JPG "github") 
![github]( https://github.com/df865017/Red_wine_label/blob/master/pic/qt_ransac/src/square1.png" github") 
![github](https://github.com/df865017/Red_wine_label/blob/master/pic/qt_ransac/src/square2.png" github") 

### 粗匹配结果
![github](https://github.com/df865017/Red_wine_label/blob/master/pic/qt_ransac/dst/sceneryRough.jpg "github") 

### 提纯后
![github](https://github.com/df865017/Red_wine_label/blob/master/pic/qt_ransac/dst/sceneryMatch.jpg "github") 


### 匹配不相关图片
![github](https://github.com/df865017/Red_wine_label/blob/master/pic/qt_ransac/dst/scenerySquare.jpg "github") 


Qt C++编写的Sift特征匹配
===================================
### 处理前
![github](https://github.com/df865017/Red_wine_label/blob/master/pic/qt_sift/name1.jpg "github") 
![github](https://github.com/df865017/Red_wine_label/blob/master/pic/qt_sift/name2.jpg "github") 

### 处理后
![github](https://github.com/df865017/Red_wine_label/blob/master/pic/qt_sift/Matches.jpg "github") 


Qt C++编写的提取汽车黑白模板
=================================== 
### 源图片
![github](https://github.com/df865017/Red_wine_label/blob/master/pic/car_mask/src/11.jpg "github") 
![github](https://github.com/df865017/Red_wine_label/blob/master/pic/car_mask/src/12.jpg "github") 
![github](https://github.com/df865017/Red_wine_label/blob/master/pic/car_mask/src/13.jpg "github") 
![github](https://github.com/df865017/Red_wine_label/blob/master/pic/car_mask/src/14.jpg "github") 
![github](https://github.com/df865017/Red_wine_label/blob/master/pic/car_mask/src/15.jpg "github") 

### 结果图片
![github](https://github.com/df865017/Red_wine_label/blob/master/pic/car_mask/result/11.jpg "github") 
![github](https://github.com/df865017/Red_wine_label/blob/master/pic/car_mask/result/12.jpg "github") 
![github](https://github.com/df865017/Red_wine_label/blob/master/pic/car_mask/result/13.jpg "github") 
![github](https://github.com/df865017/Red_wine_label/blob/master/pic/car_mask/result/14.jpg "github") 
![github](https://github.com/df865017/Red_wine_label/blob/master/pic/car_mask/result/15.jpg "github") 


综述：
===================================  
基于Opencv库实现对红酒酒标的匹配，掌握了图像的SIFT特征提取，熟悉hdf5库的分类的机制，利用边缘检测确定酒标的区域并建立黑白模板，利用Ransac算法对图像特征点匹配对提纯，降低图像旋转，尺寸缩放，图像平移，光照的变化的影响。
