## 我的Python项目

> 作者：汪瑞
>
> 说明：为了让自己学习Python更加有条理性和产出感，我将自己学习Python时实现的一些小项目记录下来，有些可能还不够完善，需要后续的补充...

### 项目1--飞机大战
- 说明：
- 1.使用Python中的Pygame包实现
- 2.目前的主要功能包括：创建窗口、创建飞机、控制飞机、发射子弹
- 3.还需要补充：子弹碰到飞机后摧毁飞机、计分...
- 4.feiji文件夹中是游戏所需要的资源

### 项目2--小说爬虫
- 说明：
- 1.非常简单的一个爬虫，用于爬取一本小说，并将小说下载到本地的txt文件中
- 2.爬取的小说网站是笔趣阁小说网站
- 3.注意到小说网站链接是https开头的，程序使用jupyter notebook编写运行没有问题，但是在pycharm上出现了问题，目前还未解决
- 4.以面向对象的方式改写之前的程序（改的不太好）

### 项目3--图片爬虫
- 说明：
- 1.爬取图片网站为[堆糖网](https://www.duitang.com/)
- 2.理解爬虫逻辑：获取网页源码-->解析-->筛选-->保存
- 3.图片网站为动态加载，不同于小说网站(静态加载)
- 4.程序中url的获取方式：在搜索框输入关键字-->按F12-->点击network-->下滑网页-->左下角出现图片-->右侧的Request URL即为所需url
