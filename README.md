# KZHomePage
 二次元卡片个人网站主页

详细内容请查看：https://blog.170601.xyz/archives/25.html 

QQ交流群：<a target="_blank" href="https://qm.qq.com/cgi-bin/qm/qr?k=-tso4BmPVXPSgqNjPhRCIg4GYZ8Llu_e&jump_from=webapi">962303102</a>

## 说明
KZHomePage是静态的个人主页网站，可以将代码托管在Github、Gitee、Gitlab、Coding、Gitcode等仓库中建立静态网站，个人主页可以分享有趣和酷的项目，在个人主页上直观的展示和快捷的访问项目；

### KZHomePage源码
> KZHomePage主页源码：https://github.com/kaygb/KZHomePage/
> 
> KZHomePage主页演示：https://future.170601.xyz/KZHomePage/

### KZHomePage美化版源码
> KZHomePage-美化主页源码：https://github.com/Aiazt/KZHomePageBeautify/
> 
> KZHomePage-美化主页演示：https://aiazt.github.io/KZHomePageBeautify/

## 使用方式

### 音乐配置
使用前请填写head内的相关配置信息

```javascript
    // 音乐设置
    let meting_music_api = "https://api.mizore.cn/meting/api.php";// meting api
    let music_server = "netease"; // 音乐服务：网易云 netease 
    let music_type = "playlist"; // 歌曲类型：歌单playlist 单首歌曲 song  专辑 album
    let music_id = "20173709"; // 歌单ID或歌曲ID或者专辑ID 20173709 29732992
    let music_order = "random"; // 音频循环顺序, 顺序播放： 'list', 随机播放：'random'
    let music_mini = false; // mini模式 吸底模式开启后此选项实效 true / false
    let music_fixed = true; // 吸底模式
    let music_volume = 0.7; // 默认音量
    let music_autoplay = true; // 自动播放
    let music_loop = "all"; // 音频循环播放, 可选值: 'all', 'one', 'none'
```

### 按钮颜色

> 按钮颜色使用bootstraap4的颜色格式，只需要修改按钮对应的class类即可改变按钮颜色
> https://v4.bootcss.com/docs/components/buttons/



<button type="button" class="btn btn-primary">Primary</button>
<button type="button" class="btn btn-secondary">Secondary</button>
<button type="button" class="btn btn-success">Success</button>
<button type="button" class="btn btn-danger">Danger</button>
<button type="button" class="btn btn-warning">Warning</button>
<button type="button" class="btn btn-info">Info</button>
<button type="button" class="btn btn-light">Light</button>
<button type="button" class="btn btn-dark">Dark</button>

![image.png](https://s2.loli.net/2022/06/25/J7LnAZ9ScpwzH6X.png)

## 依赖项目

https://github.com/metowolf/Meting

https://aplayer.js.org/

## Stargazers over time
Star Charts Github：https://github.com/caarlos0/starcharts
Star Charts：https://starchart.cc/

[![Stargazers over time](https://starchart.cc/Aiazt/KZHomePageBeautify.svg)](https://starchart.cc/Aiazt/KZHomePageBeautify)

