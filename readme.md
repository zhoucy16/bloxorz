## 游戏创意
游戏创意来源于一款比较经典的益智解谜类3D游戏《bloxorz》(中文名: 落井下石)。这款游戏的核心玩法是通过控制一个尺寸为(1,1,2)的长方体前后左右翻转，使之落入终点的洞中即可通关，如果翻转出地块边缘则会坠落，重新开始。游戏中添加了多种机关以及其他属性的地块丰富了游戏的玩法，详见游戏中的帮助动画。

## 界面设计
游戏从进入那一刻就已经开始，所以游戏主界面就是一局游戏，通过触发不同的机关进入不同的选项——帮助、选关等等，通过将方块移动到洞中进入选中的关卡。

## 游戏制作
游戏使用LayaAir3D引擎制作，发布到微信小游戏。
实现的功能：动画、地图、机关、音效、灯光、关卡、帮助、排行榜。

## 游戏亮点
1. 主界面的设计突破了游戏常用刻板格式，别出心裁地将游戏的各个细节都改造成游戏的有机组成部分。
2. 帮助界面自己录制了动图对游戏规则进行了简明清晰的介绍，比静态图文更直观易懂。
3. 这款游戏增加了一种新的玩法——通过灯光实现了视野，通过限制视野范围来增加难度、丰富玩法。
4. 主角物块通过灯光和透明度实现了宇宙魔方的视觉效果。

## 开发心得
1. 好友排行榜：微信为了保护自己的社交数据，规定好友关系链数据只能在开放数据域中获得，需要参考官方给出的方案实现好友排行榜功能。
2. 动态加载资源：微信小游戏对发布的代码包设有上限，一些资源（例如音乐、视频等）需要从服务器上加载。

注：最终代码在finally/src中，其余都是开发过程中的代码，可能有奇奇怪怪的问题