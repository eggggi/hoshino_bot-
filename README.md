# 基于hoshino_bot的扫雷小游戏
一个很普通的扫雷游戏。
目前有两个版本，一个是贵族版 mine_sweeper_duel ，一个普通版 mine_sweeper <br>
有3个默认难度：简单、普通、困难<br>
扫雷游戏所有群员都可参与(不要捣乱哦)<br>
贵族版通关默认难度，所有参与者都可获得贵族金币<br>
广告：保1200随缘600半auto公会招人，上期天秤座出了个退群内鬼，最终排名606。。qq群号729663432暮之林

## 安装
栞栞自己的bot有没有安装贵族游戏，选择对应版本直接丢到hoshino里的moudle里，然后在__bot__.py里的MODULES_ON加上"mine_sweeper"即可（不管哪个版本都是"mine_sweeper"）。<br>
**不要两个版本都丢进去啊kora**<br><br>
关于贵族版的问题，需要加上贵族决斗作者魔改的猜头像附带的daylimiter，详情请看[这里](https://github.com/Rs794613/PcrDuel/releases)的Games.add.gold.zip

## 指令表
### 游戏开启：
1. #### 扫雷<br>
	可快速开始简单难度的扫雷游戏
2. #### 扫雷(难度)<br>
	如：**扫雷 普通**<br>
	即可开始普通难度的扫雷游戏
3. #### 扫雷(雷区大小)(地雷数量)(持续时间/分钟)<br>
	如：**扫雷 10x10 5 1**<br>
	即可开启10x10大小，有5个雷，持续1分钟的自定义扫雷游戏。<br>
	注意：雷区边长不能小于3，地雷数量不能大于或等于雷区格子数量。
### 游戏开启后：
1. #### (横坐标),(纵坐标)<br>
	如：**2，3**<br>
	点击了第2列第3行的格子(逗号可用.代替)
2. #### 标记/!(横坐标),(纵坐标)<br>
	如：**标记2，3** 或 **!2,3**<br>
	标记第2列第3行的格子有地雷<br>
	再次发送则取消
3. #### 可能/未知/?(横坐标),(纵坐标)<br>
	如：**可能2，3** 或 **?2,3**<br>
	标记第2列第3行的格子可能有地雷<br>
	再次发送则取消
4. #### 结束扫雷/扫雷结束<br>
	强制结束游戏，只有管理员可以使用

## 其它
其它更多请看代码~(￣▽￣)~*<br>
（才不会告诉你我代码写得超烂的）<br>
（十分渴望优化建议 orz ）

## 感谢
十分感谢hoshino bot的创造者和各位做bot开发的老前辈们<br>
[HoshinoBot](https://github.com/Ice-Cirno/HoshinoBot)<br>
[HoshinoBot 作品索引](https://github.com/pcrbot/HoshinoBot-plugins-index)
