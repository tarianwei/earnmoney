
![Anurag’s github stats](https://github-readme-stats.vercel.app/api?username=Sunert&show_icons=true&theme=merko)

# 本仓库不再维护

## 免责声明: 

* 本仓库发布的Script项目中涉及的任何解锁和解密分析脚本，仅用于测试和学习研究，禁止用于商业用途，不能保证其合法性，准确性，完整性和有效性，请根据情况自行判断.

* Sunert对任何脚本问题概不负责，包括但不限于由任何脚本错误导致的任何损失或损害.

* 间接使用脚本的任何用户，包括但不限于建立VPS或在某些行为违反国家/地区法律或相关法规的情况下进行传播, Sunert 对于由此引起的任何隐私泄漏或其他后果概不负责.

* 请勿将Script项目的任何内容用于商业或非法目的，否则后果自负.

* 如果任何单位或个人认为该项目的脚本可能涉嫌侵犯其权利，则应及时通知并提供身份证明，所有权证明，我们将在收到认证文件后删除相关脚本.

* 任何以任何方式查看此项目的人或直接或间接使用该Script项目的任何脚本的使用者都应仔细阅读此声明。Sunert保留随时更改或补充此免责声明的权利。一旦使用并复制了任何相关脚本或Script项目的规则，则视为您已接受此免责声明.

 **您必须在下载后的24小时内从计算机或手机中完全删除以上内容.**  </br>
> ***您使用或者复制了本仓库且本人制作的任何脚本，则视为`已接受`此免责声明，请仔细阅读*** 

#### 开发者不易,请赏杯茶水费
<div align=center><img width="200" height="200" src="https://gitee.com/Sunert/ProxyConfig/raw/master/QuantumultX/Rules/Images/Complimentcode.jpeg"/></div>


### 特别感谢：

* [@chavyleung](https://github.com/chavyleung)

* [@NobyDa](https://github.com/NobyDa)

* [@lxk0301](https://github.com/lxk0301)

* [@id77_Github](https://github.com/id77)
关于本仓库 Actions Secrets 配置说明 :



<h1>关于本仓库&nbsp;Actions Secrets&nbsp;配置说明 :<br></h1>
<p>| Name | 脚本/相关YML | Value分割符 | 必须/可选 | 注意事项及样式 (其中"xxx"代表任意字符) | | :---: | :---: | :--------------: | :---: | | YOUTH_HEADER |&nbsp;中青看点&nbsp;youth.yml| # | 必须 | 请求地址: "<a href="https://kd.youth.cn/TaskCenter/getSign%22%EF%BC%8C">https://kd.youth.cn/TaskCenter/getSign"，</a><br>中青签到请求头:
    { xxx } | | YOUTH_ARTBODY | 同上 | &amp; | 必须 | 请求地址: "<a href="https://ios.baertt.com/v5/article/complete%22%EF%BC%8C">https://ios.baertt.com/v5/article/complete"，</a><br>阅读请求体: p=xxx | | YOUTH_REDBODY | 同上 | &amp; | 必须 | 请求地址: "<a href="https://ios.baertt.com/v5/article/red_packet%22%EF%BC%8C">https://ios.baertt.com/v5/article/red_packet"，</a><br>惊喜红包请求体:
    p=xxx | | YOUTH_TIME | 同上 | &amp; | 必须 | 请求地址: "<a href="https://ios.baertt.com/v5/user/app_stay.json%22%EF%BC%8C">https://ios.baertt.com/v5/user/app_stay.json"，</a><br>阅读时长请求体: p=xxx | | YOUTH_NOTIFY_CONTROL | 同上 | true/false | 可选 | 中青通知开关<br>默认当转盘次数为50或者100并且余额大于10元时推送通知
    | | | | | - | | | YOUTH_READ |&nbsp;中青阅读&nbsp;youth_read.yml| &amp;或者换行 | 必须 | 请求地址: "<a href="https://ios.baertt.com/v5/article/complete%22%EF%BC%8C">https://ios.baertt.com/v5/article/complete"，</a><br>阅读请求体: p=xxx | | | | | - | | | TXNEWS_COOKIE
    |&nbsp;腾讯新闻&nbsp;txnews.yml| &amp; | 必须 | 请求地址: "<a href="https://api.inews.qq.com/event/v1/user/event/report?%22%EF%BC%8C">https://api.inews.qq.com/event/v1/user/event/report?"，</a><br>腾讯新闻 Cookie: openxx=xxx | | TXNEWS_SIGN | 同上 | # | 必须 | 请求地址同上，
    阅读请求地址链接 | | TXNEWS_VIDEO | 同上 | # | 必须 | 请求地址同上， 视频请求地址链接 | | TXNEWS_NOTIFY_CONTROL | 同上 | true/false | 可选 | 腾讯新闻通知开关<br>默认当余额大于2元且通知间隔为50时推送通知 | | | | | - | | | DSJ_HEADERS |&nbsp;电视家&nbsp;dianshijia.yml | #或换行 | 必须 | 请求地址: "<a href="http://api.gaoqingdianshi.com/api/v2/sign/signin%22%EF%BC%8C">http://api.gaoqingdianshi.com/api/v2/sign/signin"，</a><br>签到请求头:
    { xxx } | | DSJ_DRAWAL | 同上 | #或换行 | 必须 | 请求地址: "<a href="http://api.gaoqingdianshi.com/api/v2/cash/withdrawal%22%EF%BC%8C">http://api.gaoqingdianshi.com/api/v2/cash/withdrawal"，</a><br>即提现请求地址 | | DSJ_NOTIFY_CONTROL | 同上 | true/false | 可选 | 电视家通知开关<br>默认不推送
    | | | | | - | | | WB_TOKEN |&nbsp;新浪微博&nbsp;weibo.yml | #或换行 | 必须 | 请求地址: "<a href="https://api.weibo.cn/xxx?gsid=%22%EF%BC%8C">https://api.weibo.cn/xxx?gsid="，</a><br>签到token: gsid=xxx | | WB_PAY | 同上 | #或换行 | 必须 | 请求地址: "<a href="https://pay.sc.weibo.com/aj/mobile/home/welfare/signin/do%22%EF%BC%8C">https://pay.sc.weibo.com/aj/mobile/home/welfare/signin/do"，</a><br>提现请求头
    | | | | | - | | | JD_COOKIE |&nbsp;京喜<br>jingxi.yml | &amp;或换行| 必须 | 京东cookie,多个账号的cookie使用<code>&amp;</code>隔开或者换行。具体获取参考<a href="https://github.com/lxk0301/scripts/blob/master/backUp/GetJdCookie.md">浏览器获取京东cookie教程</a>&nbsp;或者&nbsp;<a href="https://github.com/lxk0301/scripts/blob/master/backUp/GetJdCookie2.md">插件获取京东cookie教程</a>&nbsp;|
    | | | | - | | | PUSH_KEY | 微信推送 | - | 可选 | cookie失效推送<a href="http://sc.ftqq.com/3.version">server酱的微信通知</a>&nbsp;| | BARK_PUSH | BARK推送 | - | 可选 | cookie失效推送BARK这个APP,填写内容是app提供的<code>设备码</code>，例如：<a href="https://api.day.app/123">https://api.day.app/123</a>&nbsp;，那么此处的设备码就是<code>123</code>，再不懂看&nbsp;
    <a
        href="https://github.com/sss1016/ZQ_5_562_321/blob/189fc6871a73c1e52d9b8001f1c5f0c905eb3298/Task/icon/bark.jpg">这个图</a>&nbsp;| | BARK_SOUND | BARK推送 | - | 可选 | bark推送声音设置，例如<code>choo</code>,具体值请在<code>bark</code>-<code>推送铃声</code>-<code>查看所有铃声</code>&nbsp;| | TG_BOT_TOKEN | telegram推送 | - | 可选 | tg推送,填写自己申请<a href="https://t.me/BotFather">@BotFather</a>的Token,如<code>10xxx4:AAFcqxxxxgER5uw</code>&nbsp;,&nbsp;
        <a
            href="https://github.com/lxk0301/scripts/pull/37#issuecomment-692415594">具体教程</a>&nbsp;| | TG_USER_ID | telegram推送 | - | 可选 | tg推送,填写<a href="https://t.me/getuseridbot">@getuseridbot</a>中获取到的纯数字ID,&nbsp;<a href="https://github.com/lxk0301/scripts/pull/37#issuecomment-692415594">具体教程</a>&nbsp;| | DD_BOT_TOKEN | 钉钉推送
            | - | 可选 | 钉钉推送<a href="https://ding-doc.dingtalk.com/doc#/serverapi2/qf2nxq">官方文档</a>&nbsp;,只需<code><a href="https://oapi.dingtalk.com/robot/send?access_token=XXX" rel="nofollow">https://oapi.dingtalk.com/robot/send?access_token=XXX</a></code>&nbsp;等于符号后面的XXX，
            注：如果钉钉推送只填写<code>DD_BOT_TOKEN</code>，那么安全设置需勾选<code>自定义关键词</code>，内容输入输入<code>账号</code>即可，其他安全设置不要勾选 | | DD_BOT_SECRET | 钉钉推送 | - | 可选 | 密钥，机器人安全设置页面，加签一栏下面显示的SEC开头的字符串 , 注:填写了<code>DD_BOT_TOKEN</code>和<code>DD_BOT_SECRET</code>，钉钉机器人安全设置只需勾选<code>加签</code>即可，其他选项不要勾选,再不懂看&nbsp;
            <a
                href="https://github.com/sss1016/ZQ_5_562_321/blob/189fc6871a73c1e52d9b8001f1c5f0c905eb3298/Task/icon/DD_bot.png">这个图</a>&nbsp;|</p>
<h1>以上为配置方法详见<a href="https://raw.githubusercontent.com/lxk0301/scripts/master/githubAction.md">@lxk0301</a></h1>
<h2>感谢</h2><pre><code style="font-family: SFMono-Regular, Consolas, &quot;Liberation Mono&quot;, Menlo, monospace; font-size: 13.6px; margin: 0px; background-image: initial; background-position: initial; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial; border-radius: 6px; word-break: normal; white-space: pre; border: 0px; display: inline; overflow: visible; line-height: inherit; overflow-wrap: normal;">    * [@lxk0301](https://t.me/lxk0301)
    * [@chavy](https://t.me/chavyleung)</code></pre>
