# 5-6n自动捞p22用户手册

## 我该准备什么环境？
1. 一台性能强劲、网络流畅的电脑，安装Win10系统，系统的缩放为100%
2. 安装好MuMu模拟器，自定义分辨率为750x500,DPI为166，“少女前线”的图标放在第一行第一列
3. 安装好python，并安装opencv(4.2.0)、skimage(0.17.2)库，使用**管理员！ 管理员！ 管理员**身份运行

## 我一定要按照这些进行准备吗？
当然不，只要你看了理解了程序，你可以按照你自己的想法去准备

## 在5-6n捞p22需要什么样的队伍？
1. 一只狗粮，放在二队 
2. 低耗的打捞队，放在一队。由于我刚入坑1个多月，没有高星妖精，只能用3星必杀2的原型妖精凑数，因此我用的1号位是2改1技能满级H416，7号位是3改满技能小公主
3. 注意**4号位不要站人**！
4. 其他方案可参考nga

## 战损如何处理？
1. 如果有战损，请把会受伤的那位放在队伍的第1、2个位置，默认修复间隔为每100轮修复一次。当然，如果扛不住那么久，可以在程序中搜索“REPAIR_INTERVAL”，将其改成一个适合的值即可
2. 如果没有战损，可以在程序中搜索“REPAIR_INTERVAL”，将其改成9999

## 掉落的狗粮如何处理？
在人形仓库满了的时候会自动去工厂拆解人形，默认拆解4x6=24个人形，如果你想一次拆解更多，可以在程序中搜索“gotoRetire”，找到“for i in range(4):”语句，将数字改大即可

## 程序跑飞了如何处理？
确实，有时候会因为网络、机器问题卡顿了一下，导致漏了流程，这时候会自动把游戏关了重新启动

## 会被官方发现吗？
本程序是在PC端模拟鼠标操作模拟器，且所有的点击动作都是在一个矩形区域内随机选点，点击后有随机的等待间隔，最大程度避免被发现，但是我不保证，我只能告诉你我从2020年二月份到现在都没有问题，各位自辨