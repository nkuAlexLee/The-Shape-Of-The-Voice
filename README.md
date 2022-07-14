# The Shape Of The Voice
## 声之形
### 一、分工情况
• nkuAlexLee：UI 界面代码编写与交互设计，代码前后端合并，软件测试。<br>
• SakuraLong：游戏界面的逻辑代码, 游戏美术设计，素材搜集与创作。<br>
• Thoams0211：编谱界面的逻辑代码, 编谱界面的谱面设计。<br>
### 二、软件介绍 ###
该软件是一款有轨下落式音乐游戏，用户通过点击下落的滑块以获得得分。整体程序基
本功能包括：播放音乐、播放谱面、判断是否准确点击、基于得分给予用户不同的等级评价、
保存得分界面等。特别的，该程序实现自定义编谱界面，提供给用户自由创作的空间，允许
用户导入自己需要的音乐，并且保存之后可以在界面游玩。<br><br>
软件的 GitHub 地址为https://github.com/nkuAlexLee/The-Shape-Of-The-Voice/<br>
### 三、想法来源 ###
组内成员平日喜欢音乐游戏，因此想自己动手尝试编写。该软件滑块模仿借鉴市面上大
部分的有轨下落式音游，编谱界面借鉴原神编谱页面。我们希望能设计一个与用户能有良好
交互的游戏，所以我们对游戏的 UI 进行了设计，整体风格统一，页面和按钮交互性强。同时
我们希望玩家能够成为游戏的创作者，所以设计了编谱功能，能够让玩家发挥创造力。
### 四、心得体会 ###
这次可谓是经历了一次从零开始的 Qt 编程，14 天的时间里，我们很难让每个人都能较
为熟练的使用 Qt，所以我们将工作按照对于 Qt 的需求大小分类安排下去，这样虽然说我们
每个人单独并不能较好的使用 Qt，但我们三个人一起，就可以非常方便的使用 Qt，这让我
们更加意识到合作的重要性和现代社会分工将会越来越细的趋势。同时我们也意识到在合作
完成项目的时候，开始编程前的项目规划，如工作分工、具体的类和函数的规划、接口如何
处理、界面设计、界面需要完成的功能、需要留出的接口等，最好是越明确越好，使得做这
个项目的每一个人头脑中都有一个整个项目的框架。我们这次虽然做了这方面的分工与安排，
但依旧还是考虑的不够全面与细致，我们在下次进行设计的时候会更加重视这一点。
### 五、软件截图 ###
#### 1.游戏界面 ####
1）.显示得分、完成率和成功点击次数<br>
2）.对应按键按下有动画和音效，正确点击有额外动画<br>
3）.可以暂停且保留滑块状态<br>
![1.png](https://s2.loli.net/2022/07/14/iztEPAwyCevdj5X.png)
#### 2.编谱界面 ####
1）.可以选择音乐，自动生成编谱文件，实现进度条和暂停按钮控制音乐<br>
2）.编谱可以通过鼠标点击和键盘输入两种方式<br>
3）.音乐播放期间谱面随时间同步运动，也可暂停调整谱面位置进行编辑，继续后自动回正位置<br>
![2.png](https://s2.loli.net/2022/07/14/hGdNcpUyVqI935E.png)
#### 3.开始界面 ####
1）.背景为动态视频<br>
2）.按钮有对应动态效果<br>
![3.png](https://s2.loli.net/2022/07/14/6KeY7cm23WlnAR1.png)
#### 4.设置界面 ####
1）.自定义按键，游戏音量和背景音乐音量<br>
2）.记录保存在本地，继承先前修改<br>
![4.png](https://s2.loli.net/2022/07/14/MU5cp3ogFRGjd1E.png)
#### 5.选择界面 ####
1）.自动读取音乐文件夹下音乐，动态生成可拖动列表<br>
2）.读取音乐成绩记录显示评分等级<br>
![5.png](https://s2.loli.net/2022/07/14/SQJYze786lorBEN.png)
#### 6.暂停界面 ####
1）.暂停滑块运动状态和音乐<br>
![6.png](https://s2.loli.net/2022/07/14/4ZeNrFmq1Lk7sDT.png)
#### 7.结算界面 ####
1）.对成绩进行结算，动态显示评分<br>
2）.自动保存历史最好成绩于本地，可显示于选择界面<br>
3）.可对成绩截图保存<br>
![7.png](https://s2.loli.net/2022/07/14/u7CV4k5ZDfn6zr1.png)
