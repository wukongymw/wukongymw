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
<b>解压密码： wukongymw.com</b></div>
<div id="sc_shuoming">源码说明</div>
夜射全国空降USDT授权盗U秒U源码/前端html+后端PHP
<div id="sc_fankui">测试反馈</div>
测试环境：Linux系统CentOS7.6、宝塔面板、Nginx、PHP7.2、MySQL5.7，运行目录public，伪静态thinkphp，建议开启SSL

这套是用了站里的另一套二开的，后台框架是fastadmin，整体没多大改动，就只是产品类型不一样，有tg通知和余额监听功能，个人感觉价格不高

数据库修改：application/database.php 文件，数据库账号密码都是 wukong_ceshi86

监听余额的计划任务
访问url 1分钟
https://ceshi86.wkym.cc/shop/listen/listenBalance

或使用shell脚本修改成自己域名
<pre class="pure-highlightjs line-numbers"><code class="language-one">#!/bin/bash
PATH=/bin:/sbin:/usr/bin:/usr/sbin:/usr/local/bin:/usr/local/sbin:~/bin
export PATH
step=30
for (( i = 0; i &lt; 60; i=(i+step) )); do
curl -sS --connect-timeout 10 -m 60 'https://ceshi86.wkym.cc/shop/listen/listenBalance'
echo "----------------------------------------------------------------------------"
endDate=`date +"%Y-%m-%d %H:%M:%S"`
echo "★[$endDate] Successful"
echo "----------------------------------------------------------------------------"
sleep $step
done
exit 0
</code></pre>
前端： https://ceshi86.wkym.cc

后台： https://ceshi86.wkym.cc/wukongymw.php
账号： admin
密码： wukongymw.com
<div id="sc_jietu">截图展示</div>
<div id="timibbs15">前端</div>
<div id="timibbs12">

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/11/1bab5d63edb8e1f.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2025/11/1bab5d63edb8e1f.png" class="aligncenter size-full wp-image-204523" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a><a href="https://cdn.wukongymw.com/wp-content/uploads/2025/11/d1587c2f0aec124.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2025/11/d1587c2f0aec124.png" class="aligncenter size-full wp-image-204521" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/11/bcf9b921053b60a.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2025/11/bcf9b921053b60a.png" class="aligncenter size-full wp-image-204522" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

</div>
<div id="timibbs15">后台</div>
<div id="timibbs12">

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/11/c0db804c514a808.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2025/11/c0db804c514a808.png" class="aligncenter size-full wp-image-204524" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a><a href="https://cdn.wukongymw.com/wp-content/uploads/2025/11/45798d8fba3dde9.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2025/11/45798d8fba3dde9.png" class="aligncenter size-full wp-image-204525" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/11/d7926a1edee40b7.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2025/11/d7926a1edee40b7.png" class="aligncenter size-full wp-image-204526" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

</div>

<!-- ##{"timestamp":1762637298}## -->