## h5 Mini Game-Plants vs. Zombies v1.18

This project is a small h5 game implemented with native js. A lot of es6 grammar is used in the implementation. For those who are not familiar with es6 grammar, please check the relevant information first.

**demo**：[线上地址](https://yangyunhe369.github.io/h5-game-plantsVSzombies/)

**代码详解**：[博客链接](http://www.yangyunhe.me/2018/h5-game-plantsVSzombies/)

## 项目截图

![](images/screenshot1.png)

## 已完成功能：
- [x] Draw the game scene: background, sunshine scoreboard, plant card (for placing plants), plants (6 types), zombies (1 type)
- [x] Attack judgment and death judgment of plants and zombies
- [x] The character animation is realized by continuously switching and drawing frame by frame, which can draw smooth animation effects
- [x] The character animation automatically switches according to the character state. The plant animation includes (normal form, attack form), and the zombie animation includes (normal form, moving form, attack form, dying form, death form)
- [x] 阳光自动生成、植物放置需消耗阳光，僵尸随机生成
- [x] 游戏包含僵尸、植物独立胜利条件判定
- [x] 游戏状态：Loading、游戏运行、游戏暂停、游戏结束（玩家胜利）、游戏结束（僵尸胜利）

## 更新代码

v1.1  优化代码，添加向日葵，能自动生成阳光

v1.15 优化代码，修复添加新植物使同行僵尸攻击判定失效bug，添加坚果墙

v1.17 优化代码，添加樱桃炸弹

v1.18 优化代码，添加除草车可清除整行僵尸

v1.2  优化代码，添加食人花

## 下载源码

``` bash
git clone https://github.com/yangyunhe369/h5-game-plantsVSzombies.git
```

## 目录结构

```
.
├─ index.html                   // 首页html
│  
├─ css                          // css样式资源文件
├─ images                       // 图片资源文件  
└─ js
   ├─ common.js                 // 公共方法
   ├─ scene.js                  // 游戏场景相关类
   ├─ game.js                   // 游戏主要运行逻辑
   └─ main.js                   // 游戏运行主函数
```

* common.js => 引入公共方法
* scene.js => 引入游戏场景素材相关类，包括角色类、动画类
* game.js => 引入游戏引擎
* main.js => 游戏运行主函数

## 说明

如果对您有帮助，您可以点右上角 "Star" 支持一下 谢谢！ ^_^

或者您可以 "follow" 一下，我会不断开源更多的有趣的项目

## 个人简介

作者：弦云孤赫(David Yang)

职业：web前端开发工程师

爱好：网游、音乐（吉他）

## 联系方式

QQ：314786482

微信：yangyunhe_yyh

坐标：四川成都

## License

[MIT](https://github.com/yangyunhe369/h5-game-plantsVSzombies/blob/master/LICENSE)
