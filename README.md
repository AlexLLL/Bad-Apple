# Bad-Apple

'''
$git clone git@github.com:AlexLLL/Bad-Apple.git  
'''

程序设计参考网上资料：
1. 读取视频，并按一定帧率保存图片；
   常见的有potplayer提取，以及opencv提取。本着学习的原则，采用后者。
2. 将得到的图片进行灰度分析，按照“黑色字符，白色空白”的原则输出字符串；
   输出的方法也有很多，简单粗暴的终端printf打印输出，或者Excel，亦或者魔兽争霸地图版……
   经过综合比较，选择html5网页输出。（比较轻便，而且可以同步音乐。）
