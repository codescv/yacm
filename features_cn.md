# 特性列表
1. 媒体扫描可设置白名单. 默认android会扫描出sd卡下所有目录中的照片视频等, 除非你一个一个的加.nomedia文件. 这样实在很痛苦. 这里提供了一个解决方案, 在sd卡根目录下建立一个文件名为".mediascanner_whitelist", 里面是指定扫描的白名单, 例如:

```
dcim
ringtones
alarm
notifications
download
pictures
movies
podcasts
music
```

这样, 只有白名单内的目录会被扫描, 其他的会被忽略. 如果希望扫描全部sd卡, 则删掉这个文件即可.

2. 拨VPN不再强制设置锁屏密码(android这个设定实在太不合理了). 如果一定要这样的安全, 也提供了选项可以设置密码.

3. 加了两个下拉快捷方式, 一个Power键, 短按锁屏, 长按弹出电源菜单. 一个ADB开关, 开关打开时ADB启用, 并且启用"插入电源屏幕常亮", 方便调试.

4. 拨号盘增加T9拼音搜索(目前只支持拼音首字母).

5. 集成google play, gmail等google应用和框架. 使用Chrome替换了默认浏览器, Google Search替换了默认的搜索框.

6. 使用teamseven的内核, 支持双击开屏, logo键变menu, 等等

7. 基于最新CM代码, 所有改动均开源, 无预装软件.
 代码地址: https://github.com/eshock