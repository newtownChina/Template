# MyGame
 一个MonoGame游戏模板<br>
模板结构：<br>
![image](https://github.com/newtownChina/MonoGameTemplate/blob/master/Content/3.png)<br>
 功能：<br>
一、简单碰撞检测：<br>
解析Tiled（https://www.mapeditor.org/ ） 地图编辑器绘制的瓦片碰撞形状，支持由顶点构成的多边形碰撞和矩形碰撞。<br>
 瓦片矩形碰撞有三种算法：<br>
(1)瓦片逐点描边算法：根据瓦片边缘生成点状碰撞形状（宽度、高度都是1px）<br>
(2)瓦片逐行绘制矩形算法：根据瓦片边缘生成点状碰撞形状（宽为瓦片宽度，高度是1px）<br>
(3)瓦片逐行绘制矩形合并算法：根据瓦片边缘生成点状碰撞形状，并进一步将Position.X相同，宽度相同的矩形合并成一个大矩形（宽为瓦片宽度，高度是合并后大矩形高度）<br>
二、简单相机管理<br>
三、简单物理（重力等）<br>
四、简单屏幕管理（玩家视野，地图滚动）<br>
五、简单精灵管理<br>
六、简单事件管理<br>
 

预览：<br>
![image](https://github.com/newtownChina/MonoGameTemplate/blob/master/Content/1.png)<br>
![image](https://github.com/newtownChina/MonoGameTemplate/blob/master/Content/2.png)<br>
