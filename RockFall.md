RockFall : U3D太空射击游戏

关于游戏的说明

游戏预览：

![img](https://github.com/PowerSpots/Readme/blob/master/My-3D-Space-Shooter-Game/Preview_Space_Shooter.gif)


---------------------------------------------------------------<b>游戏设计：</b>---------------------------------------------------------------


游戏简介  
   
	玩家操控飞船在太空中飞行，向小行星射击并摧毁它们，防御被小行星攻击的脆弱空间站。 


设计概念

	游戏主要是关于飞船在太空中发射激光束，时长最多只需要几分钟； 
	
	游戏控制非常简单，并保持操作所需的移动和开火的最低限度； 
	
	关注对抗很多小敌人的连续短期挑战（摧毁不断来袭的小行星），而不是挑战单一Boss。
	
游戏架构：
![img](https://github.com/PowerSpots/Readme/blob/master/My-3D-Space-Shooter-Game/SketchForRockfall.jpg)	
    


游戏草图    

![img](https://github.com/PowerSpots/Readme/blob/master/My-3D-Space-Shooter-Game/SketchForRockfall.jpg)	

    小行星正在袭击空间站，玩家使用屏幕上的触控板来驾驶飞船，并按下射击按钮射出激光来摧毁小行星。 
	
	游戏中的指示器显示了小行星距离太空站还有多远，草图还显示了玩家握住设备的方式


游戏中的物理学：

    飞船总是以固定速度前进，并且没有动力；
	
	玩家不能上下翻滚飞船，任何超过限制的翻滚都会被平滑纠正。 


游戏规则
    
	玩家需要操控飞船摧毁小行星来保卫太空站，攻击太空站的小行星从各个方向不断来袭； 
	
	太空站有一定的生命值，每次被小行星攻击都会消耗一些生命值； 
	
	当生命值低于零或飞船距离太空站太远时游戏结束。


UI系统

![img](https://github.com/PowerSpots/Readme/blob/master/My-3D-Space-Shooter-Game/UI_Space_Shooter.gif)

   玩家在左侧的触控板上拖动手指来控制飞船飞行方向，使用右侧按钮射击。 
   
   游戏中会显示小行星与空间站间距离的指示器，还有暂停、恢复按钮和远离太空站的红色警告。


游戏成品

![img](https://github.com/PowerSpots/Readme/blob/master/My-3D-Space-Shooter-Game/TheFinishedGame.png)
