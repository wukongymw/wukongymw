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
KUBI多语言交易所源码/合约交易+秒合约交易+币币交易+质押生息+币币交易机器人+平台币k线走势控制/前端vue编译后+后端PHP
<div id="sc_fankui">测试反馈</div>
测试环境：Linux系统CentOS7.6、宝塔面板、Nginx、PHP7.2、MySQL5.6，根目录public，伪静态laravel5，开启ssl证书

语言：看图

wap+pc的前端，很遗憾都是编译后的，要是有源码的话就有价值了，后端laravel5框架

亲测k线结算功能正常，合约交易都是完整的，基本上所有功能都测试了一遍，暂时没有遇到问题

有质押生息功能、还可以发行平台币，控制平台币k线走势，币币交易也有机器人

整个目录全局搜索 jys110.timibbs.vip 替换为自己的域名，数据库里面也要替换域名

数据库修改：.env 里面的 timibbs_jys110

跨域：/proxy/proxy.js 将 jys110.timibbs.vip 替换为自己的域名，也可以不用管，这是跨域才用得到的

安装php扩展 fileinfo opcache redis imagemagick imap intl xsl Swoole4并且禁用所有函数

部署好之后先清除程序缓存
cd /www/wwwroot/jys110.timibbs.vip
php artisan config:cache

jys110.timibbs.vip是你自己的程序目录

nginx站点配置反向代理：
location ~/(wss|socket.io) {
# 此处改为 socket.io 后端的 ip 和端⼝即可
proxy_pass http://127.0.0.1:2000;
proxy_set_header Upgrade $http_upgrade;
proxy_set_header Connection "upgrade";
proxy_http_version 1.1;
proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for;
proxy_set_header Host $host;
}

宝塔要放行所有端口哦！

环境部署教程和计划任务在压缩包里面，就不写出来了

前端wap：https://jys110.timibbs.vip/mobile
前端pc：https://jys110.timibbs.vip/app
测试账号：timibbs
密码：123456

后台：https://jys110.timibbs.vip/timibbs
账号：timibbs
密码：timibbs.net
<div id="sc_jietu">截图展示</div>
<div id="timibbs12"><a href="https://cdn.wukongymw.com/wp-content/uploads/2024/05/f9e3499c2b92f40.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/05/f9e3499c2b92f40.png" class="aligncenter size-full wp-image-202466" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a><a href="https://cdn.wukongymw.com/wp-content/uploads/2024/05/d2c495cfa97cfe7.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/05/d2c495cfa97cfe7.png" class="aligncenter size-full wp-image-202470" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/05/0ebb8e8917ee5d8.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/05/0ebb8e8917ee5d8.png" class="aligncenter size-full wp-image-202473" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/05/3b93d9a5171cfa2.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/05/3b93d9a5171cfa2.png" class="aligncenter size-full wp-image-202469" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/05/c19f14ebb544f4f.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/05/c19f14ebb544f4f.png" class="aligncenter size-full wp-image-202467" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/05/c2fddc44c57637b.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/05/c2fddc44c57637b.png" class="aligncenter size-full wp-image-202471" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/05/912d9f1ba0b7096.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/05/912d9f1ba0b7096.png" class="aligncenter size-full wp-image-202468" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/05/8b6d06ee055c51c.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/05/8b6d06ee055c51c.png" class="aligncenter size-full wp-image-202472" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/05/68e92f8fc891d34.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/05/68e92f8fc891d34.png" class="aligncenter size-full wp-image-202465" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/05/bdf92dc52d1396d.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/05/bdf92dc52d1396d.png" class="aligncenter size-full wp-image-202474" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/05/f19fb6c1fe40319.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/05/f19fb6c1fe40319.png" class="aligncenter size-full wp-image-202475" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/05/507e4ef24b93f03.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/05/507e4ef24b93f03.png" class="aligncenter size-full wp-image-202476" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/05/4a2d10dc9f334c6.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/05/4a2d10dc9f334c6.png" class="aligncenter size-full wp-image-202477" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/05/98dbd240a290ab7.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/05/98dbd240a290ab7.png" class="aligncenter size-full wp-image-202478" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/05/1da9b6d63ee612c.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/05/1da9b6d63ee612c.png" class="aligncenter size-full wp-image-202479" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/05/c0f9b529baea5b1.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/05/c0f9b529baea5b1.png" class="aligncenter size-full wp-image-202485" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/05/cf3eb1508e6e87d.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/05/cf3eb1508e6e87d.png" class="aligncenter size-full wp-image-202484" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/05/1eb152d783c2f92.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/05/1eb152d783c2f92.png" class="aligncenter size-full wp-image-202483" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/05/d7835580b75ff98.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/05/d7835580b75ff98.png" class="aligncenter size-full wp-image-202482" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/05/5f6a3d677412a9d.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/05/5f6a3d677412a9d.png" class="aligncenter size-full wp-image-202481" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/05/d398ba199c93a75.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/05/d398ba199c93a75.png" class="aligncenter size-full wp-image-202480" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

</div>

<!-- ##{"timestamp":1715910680}## -->