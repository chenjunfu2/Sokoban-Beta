##声明：
该内测版本已被淘汰，正式版已开源，请前往 https://github.com/chenjunfu2/Sokoban 下载最新版本！

##内测1：

以.Sokoban为后缀的是过关回放录像的binary文件，本测试版可以将该文件用exe打开（比如拖拽到exe图标上或者使用命令行参数等等）会进行播放，默认时间间隔为100毫秒，如要指定播放操作间隔时间，请使用命令行参数:
“\[该exe文件名称\].exe \[录像binary文件名称\].Sokoban \[间隔时间\]”，间隔时间单位为毫秒，且不为负数。

在任意模式下过关会自动生成此binary文件，命名规则是“\[年\]-\[月\]-\[日\]-\[时\]-\[分\]-\[秒\].Sokoban”，binary文件不依赖原地图文件和其它信息，可以在没有任何game.ini的情况下使用。

在源代码完善以及功能做全后会开源，目前的开源库请前往 https://github.com/chenjunfu2/Sokoban
