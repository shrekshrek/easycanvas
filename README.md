easycanvas
============

功能简单不完善，仅供自己开发使用

##类
**EC.Object**  
元素基类，拥有如下方法：  
设置位置  
.x;  
.y;  
.position(x,y);  
增量移动  
.move(x,y);  

设置旋转角度  
.rotation;  
增量旋转  
.rotate(n);  

设置缩放比  
.scaleX;  
.scaleY;  
.scale(x,y);  

设置尺寸  
.width;  
.height;  
.size(w,h);  

添加删除子节点  
.addChild(object);  
.removeChild(object);  


**EC.Sprite**  
显示元素基类，继承自Object,是其他所有显示元素的基类。
一般用于作为容器使用，自身只会刷新位置，角度，缩放信息。没有高宽的体积信息。拥有如下方法：  
绑定事件  
.on();  

解除绑定事件  
.off();  


**EC.Stage**  
.update();  


**EC.Bitmap**  
  


**EC.Graphic**  
  


**EC.Text**  
  


欢迎研讨。QQ:274924021  



 * VERSION: 0.1.0
 * DATE: 2015-11-20
