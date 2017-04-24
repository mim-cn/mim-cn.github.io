# [欢迎莅临skybosi的GitHub主页](https://skybosi.github.io/)

### [English Version](https://skybosi.github.io/)

[这里](https://github.com/skybosi) 去我的github主页

### 联系鄙人:

|          |            |
----------:|:-------------
__姓名__   |  费德剑[skybosi](https://github.com/skybosi)
__电话__   |  15102171037
__email__  |  <skybosi_ok@163.com>
__驻地__   |  中国，上海
__期望__   |  __c/c++__
__学校__   |  河北工程大学

### 会的东西 & 开源项目:

#### __C/C++__

##### [Imaginer](https://github.com/skybosi/Imaginer)
- Construct the world with imagination, image......, imagination......, [这里](https://github.com/skybosi/skybosi.github.io/blob/master/Imaginer%E8%BF%9B%E5%B1%95.md)是整个的开发列表清单，详细的记录着项目的开发过程
- 到目前为止(2017-3-3),已经将重构后的第一个版本推送到github，重构后的代码在结构上有大面积修改，支持[NDK/JNI编译](https://github.com/skybosi/Imaginer#android)
- 模块化更加明显：
    - 数据提供者(`DPer`): 暂时仅支持bmp格式图片处理
    - 数据处理中心(`DPC`): 普通处理模块(提供常见的:平移，旋转，缩放，椭圆化等),核心处理模块(边界获取,边界内部扣取,边界及内部移动,移动时的碰撞检测)
    - 颜色/坐标系统(`MetaData`): 颜色系统仅支持(RGBA模型),坐标系统暂时仅支持笛卡尔(Cartesian)坐标
    - 工具集(`Utils`):
        - 数学表达式解析(`iGenfuner`)： 完成，有待优化，详见[iGenfuner](https://github.com/skybosi/iGenfuner) 
        - 坐标变换: 有待完善
        - 矩阵/向量操作: 基本完成,有待完善

##### [iGenfuner](https://github.com/skybosi/iGenfuner) 
- [Imaginer](https://github.com/skybosi/Imaginer)-Generate-function-er =>(iGenfuner) : 函数数学表达式的解析工具
    - 顾名思义这是一个Imaginer的工具类,用来对输入的数学表达式字符串的解析,采用中缀表达式(RPN);
    - 先对输入的字符串转化为相应的中缀表达式
    - 然后计算输入的数字，就是一个计算器的功能

- 目前支持以下功能
    - 必须的四则运算(fours operators +,-,*,/)
    - 支持() , -, !, %, ^ 
    - 支持常用数学的函数sin, cos, tan, ...  [这里sysFun](https://github.com/skybosi/iGenfuner/blob/master/README.md#function)列举了所有现在支持的数学函数
    - 支持自定义函数：  [这里user1 & user2](https://github.com/skybosi/iGenfuner/blob/master/README.md#function)

- 详细描述 见[这里](https://github.com/skybosi/iGenfuner/blob/master/README.md)
- 新增 [js版本](https://github.com/skybosi/wx-Canvas/tree/master/lib) 用在 微信小程序项目[wx-Canvas](https://github.com/skybosi/wx-Canvas) 
    - 注:暂不支持自定义函数绑定功能 [binduser](https://github.com/skybosi/iGenfuner/blob/master/README.md#function)

#### __JNI/NDK (java)__

#####  [ImaginerApp](https://github.com/skybosi/ImaginerApp)
- 这个应用的目的仅仅是为了让Imaginer更加可视化，提高其中的具体算法运行细节的清晰程度，一定程度上有利于过程调试效果展示，当然其本身作为一个应用的意 义也不能被忽视，或许未来很有可能会独立出来作为一个单独的小家伙

#### __javaScript__

####  [wx-Canvas](https://github.com/skybosi/wx-Canvas)
- 这是一个微信小程序 —— 一个简易的数学函数图像渲染器，初步目标是将 iGenfuner 的功能从c++移植到js(或者说是微信小程序中);
- 新增拖拽，坐标，函数点追踪,详见[这里](https://github.com/skybosi/wx-Canvas#example)

