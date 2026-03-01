<div id="announcement"><div>
 <h2>重要公告</h2>
    <p>
        加入我们的 Telegram 群组以获取最新消息和支持！ 
        <br>
        📢 <a href="https://t.me/wukongym" target="_blank">点击这里加入 TG 群</a>
        <br><br>
        如需帮助，请联系唯一客服：
        <br>
        🤖 <a href="https://t.me/wukongymw" target="_blank">点击这里联系客服</a>
    </p>
  </div>
</div>

<div id="sc_error">本套程序已经过悟空源码技术人员测试，如需搭建请直接联系客服：<a href="http://t.me/wukongymw">@wukongymw</a>
<b>解压密码：timibbs.net</b></div>
<div id="sc_shuoming">源码说明</div>
阿里金服二开抖音公益竞猜玩法/抖音热门话题竞猜投注游戏/机器人下注+预设开奖/前端html+后端PHP
<div id="sc_fankui">测试反馈</div>
测试环境：Linux系统CentOS7.6、宝塔、PHP7.2、MySQL5.6，根目录public，伪静态thinkPHP，开启ssl证书

数据库修改：.env 和 /config/database.php ，尽量两个位置都改成一样

服务器开放1-65535端口，PHP安装redis扩展、memcached扩展，删除全部禁用函数并重启PHP

*********************************

这套也是之前互换的，他们卖钱的玩意，好久了都，刚从垃圾站翻到的，今天有时间就测试了一下，丢给你们玩吧，产品价值取决于你们的市场需求

整体来说没太大亮点，毕竟一两年前的东西了，数据源接口能正常使用，功能较为单一

我们每测试一套源码大概都要花1-3个小时的时间，要先分析程序是否有价值、然后本地扫后门、传到服务器线上部署测试、清理数据库后门、修复/优化程序、整理搭建文档等复杂的流程，测试一套程序就相当于你们给客户搭建修复程序了。

虽然我们会在程序里面打自己的小广告，但是绝对不会主动放后门程序，对于我们来说是没这个必要也没有这个精力，所以你们拿去测试的时候尽可放心使用（当然自己拿去还是要扫一下防止我们没有清理完，并且在服务器做好安全措施，没特殊要求的话宝塔本身的防火墙就够了）

*********************************

添加宝塔计划任务
抖音热门采集：https://caipiao103.timibbs.vip/api/Api/douyinhot 每个小时执行一次
修改脚本目录 shell 里面的脚本把 caipiao103.timibbs.vip 都要修改成你网站的目录，并挨个启动
执行方式1（在本目录打开终端）: sh timibbs.sh
执行方式2（宝塔计划任务）：
cd /www/wwwroot/caipiao103.timibbs.vip/
php think ccxbstage
sleep(5)

登陆后台后修改websocket地址为自己的服务器ip

网站根目终端执行（也可以不启动，用处不大）：
php server.php start -d
php start.php start -d

测试中发现的问题：
1.程序开奖/采集逻辑有点混乱；
2.下注后，显示的都是未中奖，开奖结算应该是正常的;
3.启动robot.sh机器人脚本的时候会报错（这种玩法需要机器人吗？？）。

如果在登陆时遇到报错：A non-numeric value encountered，不要慌，挨个启动shell命令就行，然后就能正常登陆了。这是由于没有生成本时段的期号所以会报错，不是bug，可以修复也可以忽略不计

前端:https://caipiao103.timibbs.vip/
测试账号：timibbs
密码：123456

后台：https://caipiao103.timibbs.vip/admin
账号：timibbs
密码：timibbs.net
<div id="sc_jietu">截图展示</div>
<div id="timibbs12">

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/04/c374226030a34f0.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/04/c374226030a34f0.png" class="aligncenter size-full wp-image-202134" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a><a href="https://cdn.wukongymw.com/wp-content/uploads/2024/04/48e569c0dc93c47.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/04/48e569c0dc93c47.png" class="aligncenter size-full wp-image-202132" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/04/abc7005b5d59fb0.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/04/abc7005b5d59fb0.png" class="aligncenter size-full wp-image-202142" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/04/949911e76f38635.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/04/949911e76f38635.png" class="aligncenter size-full wp-image-202141" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/04/6284315c711d4a7.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/04/6284315c711d4a7.png" class="aligncenter size-full wp-image-202139" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/04/47c19c8b8d5ed88.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/04/47c19c8b8d5ed88.png" class="aligncenter size-full wp-image-202133" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/04/0de08926341dd44.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/04/0de08926341dd44.png" class="aligncenter size-full wp-image-202136" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/04/76e5adbe2058444.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/04/76e5adbe2058444.png" class="aligncenter size-full wp-image-202137" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/04/6935a4da0720885.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/04/6935a4da0720885.png" class="aligncenter size-full wp-image-202138" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/04/cdf64579d395713.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/04/cdf64579d395713.png" class="aligncenter size-full wp-image-202140" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/04/73bc8f8876e9c45.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/04/73bc8f8876e9c45.png" class="aligncenter size-full wp-image-202143" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/04/c43934490151104.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/04/c43934490151104.png" class="aligncenter size-full wp-image-202135" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

</div>

<!-- ##{"timestamp":1712022426}## -->