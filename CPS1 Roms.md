# CPS1 街机游戏兼容性列表

以 Widows 版的 RetroArch 为例，支持 CPS1 街机游戏的核心不止一个：
- Arcade (FB Alpha 2012 CPS-1)
- Arcade (FB Alpha 2012)
- Arcade (FinalBurn Neo)
- Arcade (MAME...) 系列核心

1G1R 是 1 Game 1 ROM 的缩写，意思是一个游戏只选取一个最佳版本的 ROM 文件。

下面这份 CPS1 街机游戏列表，是根据 FBNeo - Arcade Games.rdb 数据库里 ROM 文件描述，按照 1G1R 的策略收集整理的，当一个游戏有多个版本的 ROM 文件时，筛选规则如下：
1. 只支持 FinalBurn Neo，不支持 FB Alpha 2012 CPS-1 和 FB Alpha 2012 的 ROM 文件淘汰；
2. 如果不止一个版本的 ROM 文件支持多核心，优先选择没有依赖的 ROM 文件。

序号 | ROM 文件 | CRC32 | 依赖于 | 游戏名称 | 兼容性说明
--- | --- | --- | --- | --- | ---
1 | 1941.zip | 64E58DC3 | | # - 1941 反击战 | 
2 | 3wonders.zip | C1A3CC0C | | Q - 奇迹三世界 | 
3 | captcomm.zip | 903715AE | | M - 名将 | 
4 | cawing.zip | 31B0791C | | C - 雌虎战机 | FB Alpha 的两个核心不可玩：<br>第一关从云层下降到海面不久，<br>后方出现的敌机会呈现黑色，<br>游戏随后卡死 
5 | cworld2j.zip | 319BF022 | | M - 冒险问答 卡普空世界2 | 
6 | dino.zip | 5214C514 | | K - 恐龙快打 | 
7 | dynwar.zip | 13133F73 | | T - 吞食天地1 王朝战争 | 
8 | ffight.zip | E5524363 | | K - 快打旋风 | 
9 | forgottnu.zip | 916345E9 | forgottn.zip | S - 失落的世界 | FB Alpha 的两个核心不可玩：<br>部分按键无效 
10 | ghouls.zip | B5E40BEF | | D - 大魔界村 | 
11 | knights.zip | 29BC394F | | Y - 圆桌骑士 | 
12 | kod.zip | 4F51657C | | L - 龙王战士 | 
13 | mbombrd.zip | 7E214FC4 | | S - 摔角霸王1 最终之战 | 
14 | megaman.zip | 779C1CE7 | | L - 洛克人1 力量之战 (CPS1版) | 
15 | mercs.zip | DD86F423 | | Z - 战场之狼2 | 
16 | msword.zip | CF246210 | | M - 魔法剑 英雄的幻想 | 
17 | mtwins.zip | 37C648BE | | S - 双麒儿 | 
18 | nemo.zip | 2DE12145 | | M - 梦幻冒险 | 
19 | pang3.zip | 48BFD83A | | M - 魔鬼气泡3 | 
20 | pnickj.zip | 3A8E9DCB | | M - 魔法方块 | 
21 | punisher.zip | 2E7981B0 | | C - 惩罚者 | 
22 | qad.zip | BC181DDF | | L - 龙之迷题 | 
23 | qtono2j.zip | 847A5C2B | | W - 问答信长之野望2 全国版 | 
24 | sf2.zip | B62D0BC7 | | J - 街头霸王2 天下斗士 | 
25 | sf2ce.zip | 60FF7935 | | J - 街头霸王2 四大天王 | 
26 | sf2hf.zip | A86F0C6C | | J - 街头霸王2 战斗宣言 | 
27 | sfzch.zip | F9A2076F | | S - 少年街霸1 | 
28 | slammast.zip | 26EB81A2 | | S - 摔角霸王1 | 
29 | strider.zip | 329FB3E2 | | C - 出击飞龙 | 
30 | unsquad.zip | 01ADC184 | | Z - 战区88 | 
31 | varth.zip | B732BB4D | | W - 威虎战机 雷暴行动 | 
32 | willowj.zip | 573A7059 | willow.zip | W - 威洛之旅 | 
33 | wof.zip | DC01687D | | T - 吞食天地2 赤壁之战 | 

建议优先使用 Arcade (FinalBurn Neo) 核心加载游戏。

我拥有游戏手柄和街机摇杆两种设备，为了避免来回修改按键映射的麻烦，我的做法是：
- 使用手柄的时候切换到 Arcade (FinalBurn Neo) 核心，采用手柄的按键映射方案；
- 使用街机摇杆的时候切换到 Arcade (FB Alpha 2012 CPS-1) 核心，采用街机摇杆的按键映射方案。
