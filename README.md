﻿# ChaoXingAutoPlayVideo
超星尔雅全自动播放视频脚本

此脚本针对全校选修课开发，其他课程不保证可用

只支持H5播放器，如果使用时一直跳转而不播放视频可能是因为页面是老版播放器

功能：全自动后台播放视频（暂不支持一个页面多个视频的情况），可以无视播放时弹出的题目，播放完自动跳转下一个视频，支持后台播放

初次使用时：请根据自身情况调整配置信息内容

使用方法：首先确认URL为*.chaoxing.com/mycourse/studentstudy*形式，然后在非IE浏览器上按F12打开控制台（Console），将此脚本所有内容粘贴上去按回车即可。

下一步计划：预计增加自动答题功能，由于需要跨域访问网页获取题目答案，普通JS版将停止更新，功能完成后会上传Tampermonkey（油猴）版。