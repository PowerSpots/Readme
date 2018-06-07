My Side-Scrolling Action Game
This is an 'About The Game' more than a Readme.md document

Game Preview 游戏预览：
![img](null)

<b>Game Design 游戏设计：</b>
    1.Introduction  游戏简介
The player con‐ trols a garden gnome, who’s being lowered by an attached rope into a well. At the bottom of the well there’s some treasure. The catch is that the well is filled with traps that kill the gnome if he touches them. 
玩家控制一个矮人园丁，通过一根绳子进出井中。井底有一堆宝藏，但是井里充满了各种陷阱。如果矮人接触了陷阱，就会被杀死。
   ![img](PrototypeFirstVersion)
This game relies on the 2D graphics and physics features of Unity, in addition to fairly heavy use of the UI system.
这个游戏的实现依赖与Unity的2D物理和图形系统，还有内置的新UI系统。
The gnome is a “ragdoll”—a collection of pieces that are connected via joints, with each piece an independently simulated rigid body.
矮人实际上是一个玩偶：通过弹簧关节SringJoint2D连接的一堆对象，每个对象都是独立模拟的刚体。
   ![img](ConfigureTheSpringJoint2D-ConnectTheLegToTheRope) ![img](ConfigureTheSpringJoint2D-ConnectedAnchorAndTheAnchor)
The rope is made in a similar way: it’s a collection of rigid bodies, all connected to each other with joints.
绳索的制作方式类似：它由一组刚体组成，全部用关节相互连接。
The game’s camera has a script running that keeps its position linked to the vertical position of the gnome, but also keeps the camera from showing anything above the top of the well or below the bottom of the well. 
游戏相机上有一个脚本，用来保持相机位置与矮人的垂直位置相关联，同时也能防止相机显示井顶或井底以下的任何物体。

    2.Rules         游戏规则
    The rule of the gameplay is handled through very straightforward collision detection: 
    游戏规则通过直接的碰撞检测来处理：
·If any part of the gnome touches a trap object, the gnome is dead, and a new gnome is created.
如果矮人的任何部分触及一个陷阱对象，那么矮人就会死掉，并且会重新生成一个新的矮人。
·If the treasure is touched, the gnome’s sprites are updated to show that he’s holding the treasure.
如果宝藏被触碰，矮人的精灵图片将被更新以显示他握有宝藏。
·If the top of the well (an invisible object) is touched, and if the gnome is holding the treasure, the player wins the game.
如果矮人到达了井的顶部（不可见对象），此时如果矮人拿着宝藏，那么玩家将赢得游戏。

   3.Sketch         游戏草图
   ![img](ConceptSketch)

   4.UI system      UI系统
   ![img](Menu_Side_Scrolling)

   5.FinishedProduct    游戏成品
   ![img](TheFinishedProduct)
