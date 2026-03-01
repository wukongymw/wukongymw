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
<b>解压密码：wukongymw.com</b></div>
<div id="sc_shuoming">源码说明</div>
WealthFlow多语言交易所源码/加密货币+外汇+美股+期货+借贷+质押+场控输赢+模拟账号/前端uniapp编译后+后端php
<div id="sc_fankui">测试反馈</div>
测试环境：Linux系统Ubuntu22、宝塔面板、Nginx、PHP7.2、MySQL5.7，运行目录public，伪静态选择thinkphp，建议开启SSL

语言：6种，看图

这一套的功能非常多，很多功能都有，包括加密货币、外汇产品、美股产品、期货产品等，这些都可以设置期权交易属性，还有杠杆交易、借贷、质押这些功能，外汇和股票可以需要换接口

控制的话没有测试，就连k线都不需要你配置服务器环境，只要服务器ip在火币允许的名单内，前端可以直接调用k线数据，对于新手比较友好

控制分为用户场控（全赢、全输、涨赢跌随机、跌赢涨随机、涨赢跌输、跌赢涨输），杠杆交易也可以控输赢

另外这一套可以设置任何币种为平台币，后台有设置平台币k线，我没找到在哪里，你们自己研究一下

前端还有试玩账号登录，这个我觉得也有卖点，解决了用户体验时需要注册的繁琐过程

很遗憾的是，这套前端是编译后的，没有纯源码，要不然卖上万都是随随便便的事，编译后的也有价值哦，自己拿去参考

数据库修改：config/database.php 里面将 timibbs_jys120 改成你自己的，或者你自己设置账号密码都为 timibbs_jys120 即可

前端修改：新建网站将 jys120-h5.timibbs.cc_20241209_015131.tar.gz 前端文件上传并解压，使用宝塔的全局搜索软件搜索 jys120.timibbs.cc 改为你自己的后端域名，同时需要做反向代理用于代理api

前端：https://jys120-h5.timibbs.cc/
用模拟账号登录

后台：https://jys120.timibbs.cc/timibbs
账号：admin
密码：timibbs.net

伪静态添加反向代理：
<pre class="pure-highlightjs line-numbers"><code class="language-one">location /api {
	# 此处改为后端的域名 需要添加/
	proxy_pass https://ceshi11.wkym.cc/; 
	proxy_set_header Upgrade $http_upgrade; proxy_set_header Connection "upgrade";
	proxy_http_version 1.1;
	proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for;
	proxy_set_header Host $host;
  proxy_set_header X-Real-IP $remote_addr;
}

</code></pre>
添加上面反向代理的话就不要做前后端分离，直接放前端解压到public根目录，修改一下默认文档 index.html 为第一个就可以了。不会搭建的联系 TG：@wukongymw
<div id="sc_jietu">截图展示</div>
<div id="timibbs15">H5端</div>
<div id="timibbs12">

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/02/a0f0d13db8fa1ad.png"><img class="alignnone size-full wp-image-203163" src="https://cdn.wukongymw.com/wp-content/uploads/2025/02/a0f0d13db8fa1ad.png" alt="" /></a><a href="https://cdn.wukongymw.com/wp-content/uploads/2025/02/fde55856f8bcefd.png"><img class="alignnone size-full wp-image-203174" src="https://cdn.wukongymw.com/wp-content/uploads/2025/02/fde55856f8bcefd.png" alt="" /></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/02/e2ee83b8b5eaadd.png"><img class="alignnone size-full wp-image-203173" src="https://cdn.wukongymw.com/wp-content/uploads/2025/02/e2ee83b8b5eaadd.png" alt="" /></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/02/54690a288184fcb.png"><img class="alignnone size-full wp-image-203172" src="https://cdn.wukongymw.com/wp-content/uploads/2025/02/54690a288184fcb.png" alt="" /></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/02/8de4bec43f8abb9.png"><img class="alignnone size-full wp-image-203171" src="https://cdn.wukongymw.com/wp-content/uploads/2025/02/8de4bec43f8abb9.png" alt="" /></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/02/90d0f49e5e8a742.png"><img class="alignnone size-full wp-image-203170" src="https://cdn.wukongymw.com/wp-content/uploads/2025/02/90d0f49e5e8a742.png" alt="" /></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/02/25de1a2074b5a2d.png"><img class="alignnone size-full wp-image-203169" src="https://cdn.wukongymw.com/wp-content/uploads/2025/02/25de1a2074b5a2d.png" alt="" /></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/02/61045e7ff85e8d1.png"><img class="alignnone size-full wp-image-203168" src="https://cdn.wukongymw.com/wp-content/uploads/2025/02/61045e7ff85e8d1.png" alt="" /></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/02/73a1e813ff7bf7b.png"><img class="alignnone size-full wp-image-203167" src="https://cdn.wukongymw.com/wp-content/uploads/2025/02/73a1e813ff7bf7b.png" alt="" /></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/02/819848d99e44c41.png"><img class="alignnone size-medium wp-image-203166" src="https://cdn.wukongymw.com/wp-content/uploads/2025/02/819848d99e44c41.png" alt="" /></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/02/7472030ca721497.png"><img class="alignnone size-medium wp-image-203165" src="https://cdn.wukongymw.com/wp-content/uploads/2025/02/7472030ca721497.png" alt="" /></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/02/995ab26e35c5c93.png"><img class="alignnone size-medium wp-image-203164" src="https://cdn.wukongymw.com/wp-content/uploads/2025/02/995ab26e35c5c93.png" alt="" /></a>

</div>
<div id="timibbs15">后台</div>
<div id="timibbs12">

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/02/aecc24a0ef0106e.png"><img class="alignnone size-full wp-image-203175" src="https://cdn.wukongymw.com/wp-content/uploads/2025/02/aecc24a0ef0106e.png" alt="" /></a><a href="https://cdn.wukongymw.com/wp-content/uploads/2025/02/3acbd428201cd0a.png"><img class="alignnone size-medium wp-image-203176" src="https://cdn.wukongymw.com/wp-content/uploads/2025/02/3acbd428201cd0a.png" alt="" /></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/02/404c8525ca0a110.png"><img class="alignnone size-medium wp-image-203177" src="https://cdn.wukongymw.com/wp-content/uploads/2025/02/404c8525ca0a110.png" alt="" /></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/02/a45d36b95dff6b3.png"><img class="alignnone size-medium wp-image-203178" src="https://cdn.wukongymw.com/wp-content/uploads/2025/02/a45d36b95dff6b3.png" alt="" /></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/02/c4aae4bbf8e2e1f.png"><img class="alignnone size-medium wp-image-203179" src="https://cdn.wukongymw.com/wp-content/uploads/2025/02/c4aae4bbf8e2e1f.png" alt="" /></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/02/0cf456c7917c47e.png"><img class="alignnone size-medium wp-image-203180" src="https://cdn.wukongymw.com/wp-content/uploads/2025/02/0cf456c7917c47e.png" alt="" /></a>

</div>

<!-- ##{"timestamp":1738975123}## -->