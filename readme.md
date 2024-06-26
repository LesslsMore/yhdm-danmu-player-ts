# 动漫网站弹幕播放

自动匹配加载动漫剧集对应弹幕并播放，目前支持樱花动漫、风车动漫

### 支持网站

[樱花动漫、风车动漫](https://www.dmla5.com/)

## 主要功能

- 自动加载弹幕
- 手动搜索弹幕
- 手动上传弹幕

## 效果演示

### 自动加载弹幕

自动匹配加载动漫剧集对应弹幕并播放，弹幕加载和播放暂停时会显示番剧弹幕信息

![](https://raw.githubusercontent.com/LesslsMore/yhdm-danmu-player-ts/master/doc/img1.png)

### 手动搜索弹幕

比如[哭泣少女乐队](https://www.dmla5.com/play/8703-1-7.html)不能自动加载弹幕，会在视频加载和播放暂停时进行提示

在视频任意位置右键，打开菜单，将搜索番剧名称改为 girls band cry 后，按下回车键，会重新加载当前集数的弹幕

![](https://raw.githubusercontent.com/LesslsMore/yhdm-danmu-player-ts/master/doc/img3.png)

又例如 无职转生第二季 part2 未搜索到番剧弹幕，按照上面同样的方式，

将搜索名称改为 无职转生 后，按下回车键，选择 无职转生第二季 part2 后，会自动加载当前集数的弹幕

![](https://raw.githubusercontent.com/LesslsMore/yhdm-danmu-player-ts/master/doc/img5.png)

又例如 魔法科高校的劣等生第三季 未搜索到番剧弹幕，按照上面同样的方式，

将搜索名称改为 魔法科高校的劣等生 后，按下回车键，依然没有，

换成 魔法科高校 后，选择下拉列表中的 魔法科高校の劣等生 (続編)，会自动加载当前集数的弹幕

(弹弹 play 数据库没有收录中文名称)

### 手动上传弹幕

如果有本地下载好的弹幕，可以点击上传弹幕，添加 xml 格式本地弹幕

![](https://raw.githubusercontent.com/LesslsMore/yhdm-danmu-player-ts/master/doc/img2.png)

### 主要原理

根据页面获取动漫名称，通过 url 确定播放剧集，重新渲染播放器，

### 安装提示

出现如下界面，请点击总是允许此域名，该操作获取弹幕相关数据

![](https://raw.githubusercontent.com/LesslsMore/yhdm-danmu-player-ts/master/doc/img4.png)

### 特别鸣谢

[弹弹 play](https://www.dandanplay.com/) 提供弹幕服务

### 油猴脚本地址

https://greasyfork.org/zh-CN/scripts/485364

### 更新记录

0.3.3 优化完善手动搜索番剧选择功能，代码优化为事件驱动

0.3.2 显示弹幕信息，添加缓存，优化性能，记录选择的番剧

0.3.1 优化完善手动搜索剧集选择功能

### 最后

欢迎提交问题与反馈！

[issue](https://github.com/LesslsMore/yhdm-danmu-player-ts/issues)

[feedback](https://greasyfork.org/zh-CN/scripts/485364/feedback)

如果觉得有用，请转发和收藏，这就是对优化和更新的支持！


