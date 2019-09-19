<p align="center"><a href="https://sesine.com/mina" target="_blank"><img src="https://static.sesine.com/wechat-weapp-movie/logo.png" width="128" hegiht="128" alt="logo"></a></p>

# 🎬 电影推荐小程序 v2.0

🎉 查看页面UI请点击：[https://sesine.com/mina](https://sesine.com/mina/) 

🌠 此项目使用了大部分微信的api，封装了一些UI组件。如果对您有帮助，请给一个⭐️Star。如果在使用过程中发现问题，请给我 [反馈] 我会尽量在第一时间解决。

## 🔌 使用方法

1. 克隆或下载此项目
2. 在微信开发者工具导入此项目
3. 域名设置
- 如果有自己的APPID，可以使用自己的APPID，并在微信后台添加可信域名 `https://sesine.com/` 和 `https://sesine.com/mina/api/`。
- 如果没有自己的APPID，可以使用测试APPID。开发时勾选 `不校验合法域名、web-view（业务域名）、TLS 版本以及 HTTPS 证书` 的选项，如果需要在手机上预览，并且出现api无法访问的问题。请在 [微信小程序测试号管理](https://developers.weixin.qq.com/sandbox) 里面添加上一条中的二个可信域名。
4. 开发、体验与反馈。发现问题时，可以给我 [反馈]
- 豆瓣api https://sesine.com/ (代理豆瓣api)

> 由于微信服务器请求豆瓣api次数过多，已经禁止微信小程序请求。请使用新的api地址请求，请将原来的api请求地址从 `https://api.douban.com/v2/` 改为 `https://sesine.com/mina/api/` 即可，api请求的参数不变。

- 百度地图 http://lbsyun.baidu.com/

## 🚀 v2.0更新内容

- 将搜索从页面转移到首页面的搜索框
- 增加了电影与人物的浏览历史、收藏功能
- 添加“我的页面”（重头戏）
- 添加摇一摇、相册模块
- 添加设置功能，可清除缓存、编辑个人资料、查看手机信息、更新地理位置
- 添加关于页面，里面列举除了项目中所有使用到的api

