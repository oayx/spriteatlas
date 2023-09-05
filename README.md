
## 主要功能


实现了游戏运行过程中动态打图集，包括增量打图集

<br><img src='image/1.png'><br>
<br><img src='image/2.png'><br>



## 优缺点
1.可以增量打图集，如果只是增加或减少一部分图片，打图集速度很快，在1ms以内

2.只能针对大小一样的图片，如果是大小不同，需要分别打多个图集


## 待改进的地方
1.未实现图集整理功能，可以降低空闲slice的数量