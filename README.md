# [Welcome to skybosi's GitHub Pages](https://skybosi.github.io/)

###  [中文版](https://skybosi.github.io/README-zh.html)

You can click [Here](https://github.com/skybosi) to get the message of mine !

Then here is some info. of myself

|          |            |
----------:|:-------------
__Name__   |  [skybosi](https://github.com/skybosi)
__Phone__  |  15102171037
__email__  |  <skybosi_ok@163.com>
__Where__  |  Shanghai, China
__Wanted__ |  __c/c++__
__School__ |  Hebei University Of Engineering

## Skill

### __C/C++__

#### [Imaginer](https://github.com/skybosi/Imaginer)
- Construct the world with imagination, image......, imagination......, [Here](https://github.com/skybosi/skybosi.github.io/blob/master/Imaginer%E8%BF%9B%E5%B1%95.md) show the Imaginer Development List
- Now(2017-3-3) recode version is push,To a large extent changed the overall architecture of the code,Support [NDK/JNI complie](https://github.com/skybosi/Imaginer#android) or
can see [ImaginerApp](https://github.com/skybosi/ImaginerApp),Support windows and linux/unix
- modules:
    - data provider(`Dper`): Temporarily only support `bmp` format image processing
    - Data processing center(`DPC`):
        - Common processing module (provides common: translation, rotation, zoom, oval, etc.)
        - the core processing module (boundary acquisition, boundary internal deduction, boundary and internal movement, movement collision detection)
    - color/Coordinate system (`MetaData`): The color system only supports (RGBA model), the coordinate system temporarily supports only Cartesian coordinates
    - Utils (`Utils`):
        - Mathematical expression analysis(`iGenfuner`): detail see here [iGenfuner](https://github.com/skybosi/iGenfuner)
        - Coordinate transformation: Need to be improved!
        - Matrix / vector operation: basic completion, Need to be improved!

#### [iGenfuner](https://github.com/skybosi/iGenfuner) 
- [Imaginer](https://github.com/skybosi/Imaginer)-Generate-function-er =>(iGenfuner) : Function generator and parser
- From this class name,you can know this a utils for Imaginer,It's use to parser(use RPN) a input string, maybe a math function or a math expression;
- From the parser result,must Generate a operate stream (op-stream), to save/record the function or expression Each step of the process;
- Then while you want to get a Special value(eg:1,2,3...),Will use the recorded op-stream, step-by-step calculation until the final results

- From the name You can know is a Utils for Imaginer,It's a parser of the math expression,use to parser a string expression
    and then get Each value's function value you want.Now It's support:    
    - Elementary arithmetic(fours operators +,-,*,/)
    - () , -, !, %
    - sin, cos, tan, ... [sysFun](https://github.com/skybosi/iGenfuner/blob/master/README.md#function)
    - Custom math function： [user1 & user2](https://github.com/skybosi/iGenfuner/blob/master/README.md#function)

- Detail descripe [see here](https://github.com/skybosi/iGenfuner/blob/master/README.md)
- Add [js version Genfuner](https://github.com/skybosi/wx-Canvas/tree/master/lib) for [wx-Canvas](https://github.com/skybosi/wx-Canvas),Just want to use at WeChat-small-program 
    - NOTE:The [binduser](https://github.com/skybosi/iGenfuner/blob/master/README.md#function) function is missing

### __JNI/NDK (java)__

####  [ImaginerApp](https://github.com/skybosi/ImaginerApp)
- The purpose of this application is simply to let Imaginer more visual, improve the specific algorithm execution details of clarity, extent
have to process the debugging results show, of course its significance as an application cannot be ignored, perhaps in the future is likely to
will stand out as a separate small guy

### __javaScript__

####  [wx-Canvas](https://github.com/skybosi/wx-Canvas)
- This is small-app on the wechat - A small image renderer use to WeChat-small-program,jsut want to transplant draw math function image from c++ to js (or we-chat);
Now can work well!
- Add drag, coordinate, function point tracking, see [here](https://github.com/skybosi/wx-Canvas#example)

