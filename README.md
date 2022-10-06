# Calcium Bot

机器人QQ: 1909422218 (calcium-bot)

维护: 893667349 (Satori/CalciumSilicate)

## B站信息推送 (haruka_bot)

输入 `!帮助` 获取帮助信息

## B站链接解析 (nonebot_plugin_analysis_bilibili)

直接将视频/动态/专栏等链接或AV/BV号发送至群聊中

## 点歌 (nonebot_plugin_simplemusic)

支持QQ音乐、网易云、酷我、酷狗、咪咕、B站音频区

使用方法：`!点歌/qq点歌/网易点歌/酷我点歌/酷狗点歌/咪咕点歌/b站点歌 + 关键词`

默认为QQ点歌

## LOL比赛查询 (nonebot_plugin_lolmatch)

`!lol` 查看今日比赛信息

`!lol 本周` 查看本周比赛信息

`!lol 详情` [matchID] 查询指定比赛详细信息

`!lol 订阅` [tournamentID] 订阅联赛 每晚检查当日结果和第二天赛程

`!lol 查看订阅` 查看已订阅的所有联赛

`!lol 联赛` 查看所有即将进行或正在进行的联赛和tournamentID

`!lol 联赛详情` [tournamentID] 查看所选联赛近期已完成的赛事获取 [matchID]

## 谁AT我？ (nonebot_plugin_who_at_me)

`谁艾特我` 查看谁艾特我

## 图像超分辨率重建 (nonebot_plugin_RealESRGAN)

本插件是使用超分辨率来对图像进行重建，可以简单理解成让图片变大变清晰。

`!重建/real-esrgan/超分辨率重建/esrgan/real_esrgan` 开始操作

## [Mania]段位ACC计算器 (mania_calculator)

`!mdan list` 查看段位列表 (目前支持Reform, Malodyv2, Malodyv3和自定义，如果需要更多支持可以找硅酸钙)

`!mdan <dan> <1st> <2st> <3rd> <4th>` 计算单曲ACC

`!imdan <dan> <1st> <2st> <3rd> <4th>` 通过单曲ACC计算段位ACC (用于评估自己是否能过整段)

## [Malody]谱面速度修改 (mania-bpm-changer.py)

注意：只支持Malody

`!sc up` 开始操作

## 计算器 (calculator.py)

`!calc 算式` 简单的计算

如`!calc 2**5` 计算2的五次方

## [Cytus]黑P计算器 (black_perfect.py)

`!bp <TP> <C.Perfect> <Good> <Bad> <Miss>` 计算黑P数量

`!bp <C.Perfect> <Perfect> <Good> <Bad> <Miss>` 通过成绩计算TP

## 色图 (nonebot_plugin_setu)

| 命令                               | 举例                                | 说明                                                                                   |
|----------------------------------|-----------------------------------|:-------------------------------------------------------------------------------------|
| 下载涩图/色图+数量                       | 下载涩图12345、下载色图12345               | 下载涩图：下载非涩涩图片；下载色图：下载色色图片                                                             |
| 涩图、setu、无内鬼、色图                   | setu                              | 发送图片                                                                                 |
| @用户cd+时间（秒）                      | @张三cd12345                        | 指定用户cd                                                                               |
| 群cd+时间（秒）                        | 群cd12345                          | 指定群cd                                                                                |
| 开启/关闭在线发图                        | 开启在线发图                            | 在线发图开启之后，图片将不再从本地发送而是从网上下载后在线发送，不会占用服务器存储资源                                          |
| 涩图tagA和B和C（最多指定三个tag）            | 涩图tag碧蓝航线、涩图tag公主连结和白丝            | 为了保证尽可能多地获取tag指定的内容，tag指定的图片都会在线获取而不从本地寻找，是否存储依然遵循在线发图开关                             |
| 撤回间隔+时间（秒）                       | 撤回间隔20、撤回间隔0                      | 设置撤回间隔之后，机器人将会在指定间隔后撤回发送的图片，撤回间隔为0时，机器人将不会进行撤回。同时撤回间隔以群聊为单位，每个群都能设置不同的间隔，私聊将不会触发撤回操作 |

部分命令仅允许管理员操作，已添加管理员有CalciumSilicate, ADHeinz, Resio

## 鸣谢

- [Ptolemy](https://space.bilibili.com/46465090): https://space.bilibili.com/46465090
