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
WK Club全开源修复版海外游戏源码/WinGo+K3+5D+Slots电子游戏/前端html+后端node.js

<div id="sc_fankui">测试反馈</div>
测试环境：Linux系统CentOS7.6、宝塔面板、Nginx、Nodev16.2、MySQL5.7，根据情况开启SSL

这套算是这个系列比较完整的了，前端大部分页面都正常，而且测试开奖、下注、结算都正常，下面写的教程也很细节，不像其他人只发文章 不管客户会不会搭建

nodejs的环境一定要看仔细，启动项选择：start:node src/server.js

前端使用ejs模板渲染，后端是node.js，页面响应速度还不错，不亚于vue

1、修复了数据表admin_ac不能导入的问题；
2、修复了WinGo不能下注的bug；
3、修复了安装node_modules依赖包时的错误，把 bcrypt 换成了 bcryptjs ；

目前还存在的问题：有一些api控制器文件缺失、css文件缺失（不过也没有影响UI）、js页面文件缺失

<strong>能够正常跑的一个版本</strong>，pg电子游戏没有对接，因为没有找到接口商开户，虽然找到了接口商户的登录地址，但是需要接口商那边开户才行，所以这一块就没测了

node_modules安装有点费劲，可能是由于服务器环境问题，测试用的是CentOS7，你们可以换成CentOS9应该就没啥问题了，毕竟依赖已经安装好

后台登录的话，需要在数据表 users 的 level 字段将 0 改成1 ，然后用这个账户登录前端在右下角的个人中心找到 Admin Zone 这个功能，就是后台地址了，或者直接打开后台地址（下面会写）

免费下载了，给终身会员的福利，需要完整修复的话可以联系我 TG：@wukongymw ，价格不贵，经济实惠。不修复pg电子游戏用自带的也够用了

数据库修改：.env 里面将 wukong_ceshi37 改成你自己的，或者你自己设置账号密码都为 wukong_ceshi37 即可

前端：https://ceshi37.wkym.cc
测试账号：8888888888 （10个8）
密码：123456

后台：https://ceshi37.wkym.cc/admin/manager/index （登不上就用上面先登录前端的方法）
账号：前端账号
密码：前端密码

<div id="timibbs15">node环境</div><div id="timibbs12">
<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/06/4eb250af80b405f.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2025/06/4eb250af80b405f.png" class="aligncenter size-full wp-image-203857" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>
</div>


<div id="sc_jietu">截图展示</div>

<div id="timibbs15">前端</div><div id="timibbs12">
<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/06/a809254e436e9f5.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2025/06/a809254e436e9f5.png" class="aligncenter size-full wp-image-203841" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/06/382a566bfb77606.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2025/06/382a566bfb77606.png" class="aligncenter size-full wp-image-203842" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/06/3d333fe2f94b77d.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2025/06/3d333fe2f94b77d.png" class="aligncenter size-full wp-image-203843" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/06/e3019f12e125a55.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2025/06/e3019f12e125a55.png" class="aligncenter size-full wp-image-203846" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/06/96a4c696d186f1b.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2025/06/96a4c696d186f1b.png" class="aligncenter size-full wp-image-203847" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/06/8eb645be1d6974e.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2025/06/8eb645be1d6974e.png" class="aligncenter size-full wp-image-203848" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/06/a4f53e92c1a771c.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2025/06/a4f53e92c1a771c.png" class="aligncenter size-full wp-image-203849" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/06/39028bb351ff3e1.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2025/06/39028bb351ff3e1.png" class="aligncenter size-full wp-image-203850" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/06/5d8bc75f193c86b.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2025/06/5d8bc75f193c86b.png" class="aligncenter size-full wp-image-203851" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/06/b423d7d2247dc79.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2025/06/b423d7d2247dc79.png" class="aligncenter size-full wp-image-203852" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/06/e74af3a98a8c209.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2025/06/e74af3a98a8c209.png" class="aligncenter size-full wp-image-203844" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/06/b4a199c9c88f40b.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2025/06/b4a199c9c88f40b.png" class="aligncenter size-full wp-image-203853" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/06/90a971188398e20.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2025/06/90a971188398e20.png" class="aligncenter size-full wp-image-203845" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/06/dadf76585723ef6.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2025/06/dadf76585723ef6.png" class="aligncenter size-full wp-image-203854" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/06/ad12c3661922c3e.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2025/06/ad12c3661922c3e.png" class="aligncenter size-full wp-image-203855" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>
</div>
<div id="timibbs15">后台</div><div id="timibbs12">
<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/06/309323eb34c4378.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2025/06/309323eb34c4378.png" class="aligncenter size-full wp-image-203856" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/06/1a5f3f44218ae04.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2025/06/1a5f3f44218ae04.png" class="aligncenter size-full wp-image-203858" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/06/01a9cf701feec30.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2025/06/01a9cf701feec30.png" class="aligncenter size-full wp-image-203859" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/06/ea02cb75352886c.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2025/06/ea02cb75352886c.png" class="aligncenter size-full wp-image-203860" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/06/f00cc7cf37df408.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2025/06/f00cc7cf37df408.png" class="aligncenter size-full wp-image-203861" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/06/d1dd135be0d6dda.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2025/06/d1dd135be0d6dda.png" class="aligncenter size-full wp-image-203862" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>
</div>


<!-- ##{"timestamp":1749251577}## -->