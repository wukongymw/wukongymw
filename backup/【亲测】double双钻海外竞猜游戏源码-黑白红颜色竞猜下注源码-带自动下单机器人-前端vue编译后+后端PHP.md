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
double双钻海外竞猜游戏源码/黑白红颜色竞猜下注源码/带自动下单机器人/前端vue编译后+后端PHP
<div id="sc_fankui">测试反馈</div>
测试环境：Linux系统CentOS7.6、宝塔、PHP7.3、MySQL5.6，根目录public，伪静态参考下面，开启ssl证书

语言：葡萄牙语

单语言，前端vue编译后的，只是提供研究，不建议直接运营

我也没玩懂这个玩意，所以只是看了一下功能，没有进行游戏（搞不懂）

数据库修改：根目录下面 .env 第23、24、25行

后端域名修改：根目录下面 .env 第5行

前端域名修改：/public/static/js 下面的 index.32b86ddf.js ，打开搜索 double.timibbs.vip 替换为自己的后端域名

前端修改：修改默认文档 index.html 为第一个， index.php 改成第二个 ，或者前端直接访问 后台域名/index.html

伪静态设置
location / {
try_files $uri $uri/ /index.php?$query_string;
}
location ~* ^/ws {
access_log off;
proxy_pass http://localhost:2350;
proxy_set_header X-Real-IP $remote_addr;
proxy_set_header Host $host;
proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for;
# WebSocket support (nginx 1.4)
proxy_http_version 1.1;
proxy_set_header Upgrade $http_upgrade;
proxy_set_header Connection "upgrade";
}

计划任务：

开始游戏
php artisan game:start

未处理订单自动拒绝
php artisan withdrawBack

Workerman
php artisan workman start --d

前端测试账号：timibbs.net@gmail.com
密码：123456

后台：/timibbs
账号：timibbs
密码：timibbs.net
<div id="sc_jietu">截图展示</div>
<div id="timibbs12"><a href="https://cdn.wukongymw.com/wp-content/uploads/2024/02/aa5d53a38a52f91.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/02/aa5d53a38a52f91.png" class="aligncenter size-full wp-image-201766" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a><a href="https://cdn.wukongymw.com/wp-content/uploads/2024/02/f32ec48bfff32dd.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/02/f32ec48bfff32dd.png" class="aligncenter size-full wp-image-201762" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/02/d9a676d0a549d80.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/02/d9a676d0a549d80.png" class="aligncenter size-full wp-image-201770" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/02/c1f0e0288e8b9af.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/02/c1f0e0288e8b9af.png" class="aligncenter size-full wp-image-201768" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/02/52b2dfb4ba75505.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/02/52b2dfb4ba75505.png" class="aligncenter size-full wp-image-201767" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/02/8a3c5b3e0b52cf1.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/02/8a3c5b3e0b52cf1.png" class="aligncenter size-full wp-image-201765" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/02/dd898c5eba104ed.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/02/dd898c5eba104ed.png" class="aligncenter size-full wp-image-201764" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/02/f53581b23d2017d.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/02/f53581b23d2017d.png" class="aligncenter size-full wp-image-201759" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/02/498aaf1519304cd.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/02/498aaf1519304cd.png" class="aligncenter size-full wp-image-201761" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/02/93d508247701e44.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/02/93d508247701e44.png" class="aligncenter size-full wp-image-201769" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/02/812c8892902c418.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/02/812c8892902c418.png" class="aligncenter size-full wp-image-201760" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2024/02/c4896bdf28ef1a0.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2024/02/c4896bdf28ef1a0.png" class="aligncenter size-full wp-image-201763" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

</div>

<!-- ##{"timestamp":1707091797}## -->