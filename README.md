# Bilibili-Manga  漫画自动签到

### 这个程序有什么用?

可以帮助你自动登陆签到 B 站 \"哔哩哔哩漫画\" 


### 如何使用?

#### 方法一 使用 Github Actions(最简单, 推荐)

 B 站[视频教程](https://www.bilibili.com/video/BV19p4y1Y7GN/).

**本项目需要设置的 Secrets:**

| 名称     | 内容           |   类型     |
| -------- | ------------- |  ------ |
| ACCOUNT  | 你的B站用户名   | 必写参数 |
| PASSWORD | 你的B站密码     | 必写参数 |
| PUSH_KEY | Server酱SCKEY值 | 可选参数 |

[Server酱-微信推送](https://sc.ftqq.com/) 可直接使用你所注册的Github账号登陆，登录成功后点击'发送信息' 复制您的SCKEY值即可，具体微信绑定方式请查看Server酱 微信推送

**本项目默认设置**: 每天 0 点自动打卡签到. (由于Github运行规则，可能将会延迟一定时间)

#### 方法二 直接运行 Python(不推荐)

1. 找任意一台安装好 Python 3.6 或以上版本的服务器
2. 在任意目录下执行 `git clone https://github.com/BlueskyClouds/Bilibili-Manga && cd Bilibili-Manga`
3. 使用 pip 安装依赖库, 参考命令`pip3 install requests rsa chardet`
4. 使用 Cron 每日执行 `python3 manga_sign.py`

#### 请勿重复多次修改本文件，您每一次修改就会新增一次Actions  建议仅保留一个，删除掉其余的。
# 项目更新
[保持和原作者同步的代码更新](https://blog.blueskyclouds.com/jsfx/58.html)

#### 其他项目：
* [爱奇艺签到](https://github.com/BlueskyClouds/iQIYI-DailyBonus)
1
