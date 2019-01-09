## e203_Two-stageTo Three-stage
蜂鸟E200开源处理器核心

[Image text](https://github.com/LEAUQEAAN/e203_Four-stageToFive-stage/blob/master/2_3.png)

![Image text](https://github.com/LEAUQEAAN/e203_Four-stageToFive-stage/blob/master/2_3_pro.png)

二级流水转化为三级流水步骤：
*   1.从EXU抽取出Decode模块
*   2.把EXU的寄存器移到Decode模块
*   3.给Decode模块添加的时钟
*   4.在Decode模块添加与EXU的握手协议
*   5.在Decode模块添加延时再把数据传给EXU
*   6.处理由于延迟导致的问题【WAR】

 首先下载：https://github.com/LEAUQEAAN/e200_opensource

 下载本项目
 
 将本项目的core替换解压后文件夹里的rtl\e203\core目录
 
 将本项目的verilator替换解压后文件夹里的rtl\verilator目录

 安装verilator进入verilator目录里的readme.md进行了解



