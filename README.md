# Jave-Language
#### 置顶通知
- 如果源码文件消失了，说明被我手误删了。等等就好了
- 这个东西就是搞笑的，一切关于人物或发生的事件都是杜撰的
- 这个东西和 Java 语言没有任何关系。就像我说的，这就是个搞笑的东西
- 为什么这么多c语言的玩意？因为都是依赖项
#### 介绍
1.  只是一个好玩的项目，梗来自于一位打着我的世界旗号的所谓[反迷你人士](https://space.bilibili.com/445691468)，[梗出处点这](https://www.bilibili.com/video/BV137411t7Af#reply2358299858)
2.  教程：[点这里](tutorial.md)
3.  语言的介绍！[看这个](brief_introduction.md)

作者不是专业人员（我就是个中学生！高中还没开学闲得慌），也几乎没学过什么编译原理，就像我说的，这玩意只是拿来好玩
#### 软件架构
软件架构说明


#### 安装教程

1.  爱咋地咋地
2.  略
3.  略

#### 使用说明

1.  直接运行`jruntime.py`，在里面输入文件名可以运行程序，我这里有个演示程序，`calc.jave`
2.  自己看`jruntime.py`也能大概明白一些东西
3.  不要看`jbuiltins.py`，里面全是些脱裤子放屁的玩意
4.  懒得写了，反正没人看
#### 注意事项
1. IDE 只能使用 Word 或者 c++（雾），否则会出现问题，至于是什么问题只有寥若星辰吖博士知道
2. 源代码文件只能放在c盘，个中原因寥若星辰吖博士已经告诉我们了：不兼容其它盘。至于为什么不兼容我也不知道——我的就兼容其它盘啊！
3. 源码文件后缀只能为 .jave，虽然博士他没要求，不过我觉得我们还是自觉点。=w=
#### 语言逻辑
1.  不能乱用关键字`|`与`&`
2.  一行代码包括：
    - 指令
    - 参数，最多两个
    - 跳转到的行数，用于代码逻辑
    - 分隔符
    - sample:
    `j+|1|2|2`
3.  变量和常量除了定义，都要在前面加上`?`，两个问号可以代表一个问号字符，一个问号会在运行时被认为是变量
4.  在变量定义和获取输入时加上强制类型转换符（包括 &i, int; &f, float; &s, string）可以消除歧义，其中获取输入时强制要求类型转换符
5.  不懂的[自己看](tutorial.md)
#### 其它
![jave的起源](https://images.gitee.com/uploads/images/2021/0720/174851_c2a9ca1b_7791515.png "jave的起源！")

 _原来就是你发明的 jave 啊！_ 
