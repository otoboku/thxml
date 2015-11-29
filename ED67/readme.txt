使用foobar2000循环播放轨迹系列的BGM

需要foobar2000 1.1以上版本

使用方法：
把foo_thbgm.dll放到foobar2000的components目录下
把thxml文件放到游戏的BGM目录下
用foobar2000打开thxml文件

在foobar2000的playback目录下新增了三个选项
loop forever模式下bgm会一直循环（注：部分bgm不含loop成分）
loop count手动设置循环次数
read raw metadata选中时会直接读取bgm文件的信息，这种方式更精确，但是会降低解包的速度，所以默认关闭
（播放轨迹系列音乐不涉及解包，建议选中）



为了浏览方便，把文件名作为了ARTIST信息
以下文件无循环信息
ED_SORA1：ED6500 ED6501 ED6502
ED_SORA2：ED6500 ED6501 ED6502 ED6011 ED6012 ED6552
ED_SORA3：ED6500 ED6501 ED6502 ED6011 ED6012 ED6552 ED6021 ED6022
ED_ZERO：ed7002 ed7003
ED_AO：ed7052 ed7053 ed7460 ed7555 ed7578 ed7591


相关说明
1. 插件来源及介绍：ra.gg/!zoZa1
2. 零之轨迹/碧之轨迹 循环信息取自acgngca：tieba.baidu.com/p/1265259942
3. BGM标题大部分取自 极_幻影奇袭_改 整理的版本