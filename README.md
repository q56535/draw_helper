
# draw_helper 转型为收集游戏 以前版本在releases
以前下载过的使用前需执行指令   更新干员数据


#
2022/9/23
修复新增皮肤遇到没有先前皮肤的干员报错的问题
仅一行代码
可以等近期上线月卡功能后统一更新（设计卡片鸽了了一段时间）
#
2022/9/16

发现检测到新增干员后也跳过了星级录入

解决办法：更新代码 或 再次录入干员数据

另外存在错误的皮肤信息则会新增皮肤失败，需要强制更新干员
#
2022/9/15

修复昨晚的记录倒序bug

#
2022/9/14

新增 【更新干员数据 新增皮肤】功能， 自动更新全部新皮肤

检测新增干员跳过皮肤录入

我的干员 我的六星记录 根据星级将名字变为彩色并且改为倒叙排列

新增抽干员30秒后撤回

忘写了，所有立绘改为合并消息， 默认价格改为10


#
2022/9/4

闲的将星级录入改为异步（速度提升上十倍）（另外忘说了，txt信息录入后可以删掉txt，这样更新干员数据就不会有大量跳过提示了，这是一开始就设计好的）

2022/8/29

修复星级录入失败的问题，仅一行
增加干员录入失败跳过并提醒，增加容错

十连改为一张图片，解决风控问题

![RBITHWIY4MLT%VRS2`Z`HW8](https://user-images.githubusercontent.com/94435821/187234432-09b94c14-ee8f-4e4c-85c9-57f83eb57bd2.jpg)

#
十连可能会出现风控
#
![image](https://user-images.githubusercontent.com/94435821/187121038-7051748b-e427-4036-b1f7-21dc5beef325.png)
#
![image](https://user-images.githubusercontent.com/94435821/187121918-78006097-a104-45c7-b827-1f4887cdcae8.png)
#

#
![image](https://user-images.githubusercontent.com/94435821/187122134-34f34dbf-2356-4d1c-918c-fa0f0a2ae7c6.png)
#
真寻bot插件 抽明日方舟助理 数据来自prts.wiki 
转型收集游戏中，咕咕咕...
#
没有技术，图片数据是硬试出来的，有因为网络波动录错和少录的立绘网址，请私聊强制更新个别干员，全部更新会跳过更新数据库已有的，达不到更新的效果
#
强制更新或者新增干员会进行大量异步请求，届时网络可能受到一丝丝影响

cd请自行设置,默认180秒

切换立绘几是永久的，抽出来的时候显示是原始，我的助理显示是立绘几，如果超出索引则不予显示
#
功能 抽助理 我的助理 查看助理所有立绘 切换立绘[num] 助理随机语音？[中文]

#
2022/8/20
新增助理随机语音功能

#

![IMG_20220818_081447](https://user-images.githubusercontent.com/94435821/185560720-c5c40b96-0e8a-46ba-8ea6-4a3bf6f0259f.jpg)

悲！！！
