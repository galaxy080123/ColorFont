# ColorFont

控制台打印彩色字体

安装方法：

python setup.py install

使用方法：

0 = 黑色       8 = 灰色

1 = 蓝色       9 = 淡蓝色

2 = 绿色       A = 淡绿色

3 = 浅绿色     B = 淡浅绿色

4 = 红色       C = 淡红色

5 = 紫色       D = 淡紫色

6 = 黄色       E = 淡黄色

7 = 白色       F = 亮白色


格式：

0x12

高位代表背景色，低位代表字体颜色


0x10 | 0x02

0x10代表背景色，0x02代表字体颜色

举例：

import ColorFont

ColorFont.Color.printColoredText('hello', ColorFont.Color.font_color['blue'], ColorFont.Color.bg_color['light_green'], '\n')
