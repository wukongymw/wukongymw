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

USDT自动上分是通过官方 https://api.trongrid.io 查询接口实现的

在给一个客户做大富彩票自动充值的时候保存的代码，分享给有需要的朋友，不用再去找网上那些带后门的程序了，当然前提是 你得会PHP

只是一个前端充值自动查询并处理的代码，仅供参考，需要前端传参（订单号）后才能进行处理，同样数据库字段也得处理

<a href="https://cdn.wukongymw.com/wp-content/uploads/2023/12/1703098112-45b985652019f9e.jpg"><img src="https://cdn.wukongymw.com/wp-content/uploads/2023/12/1703098112-45b985652019f9e.jpg" width="356" height="771" class="aligncenter size-full wp-image-201008" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

[video width="384" height="848" mp4="https://cdn.wukongymw.com/wp-content/uploads/2023/12/1703098115-a84d99476673583.mp4"][/video]

<div id="sc_redb">代码如下：</div>


[php]
function timibbs_usdtautopay($apiparam=array()){
	$apiparam = self::_cheacktoken($apiparam);
	if(!$apiparam['sign'])return $apiparam;
	$trano = $apiparam['trano'];
	$payorder = M('recharge')-&gt;where(['trano'=&gt;$trano,'state'=&gt;0])-&gt;find();

        //查询平台收款地址
        $usdtpayaddress = M('payset')-&gt;field(&quot;ftitle&quot;)-&gt;where(&quot;isonline=-1 AND state=1 AND paytype='USDT'&quot;)-&gt;find();
        $to_address = $usdtpayaddress['ftitle'];
	
	//获取地址交易记录
        $url = &quot;https://api.trongrid.io/v1/accounts/$to_address/transactions/trc20?limit=10&amp;contract_address=TR7NHqjeKQxGTCi8q8ZY4pL8otSzgjLj6t&quot;;
        $getData = file_get_contents($url);
        $jsonData = json_decode($getData,true);

        //循环查询链上记录
        foreach ($jsonData[&quot;data&quot;] as $k=&gt;$v){
            //这里注释掉了，单一订单查询没必要循环所有订单
            // foreach ($payorder as $a=&gt;$b){
                $from_address = $payorder[&quot;from_address&quot;];
        	$usdtnum = $payorder[&quot;usdtnum&quot;];

                //转账时间必须大于创建订单时间
                if($v['block_timestamp']/1000 &gt; $payorder['oddtime']){

                    //转账地址、数量完全匹配
                    if($v['to'] == $to_address &amp;&amp; $v['from'] == $from_address &amp;&amp; $v['value']/1000000 == $usdtnum){
                        $userinfo = M('member')-&gt;where(['id'=&gt;$payorder['uid']])-&gt;find();
                        $add['oldaccountmoney'] = $userinfo[&quot;balance&quot;];
                        $add['newaccountmoney'] = $userinfo[&quot;balance&quot;] + $payorder['amount'];
                        $add['state'] = 1;
                        $add['transaction_id'] = $v[&quot;transaction_id&quot;];//哈希值
                        M('recharge')-&gt;where(['trano'=&gt;$trano])-&gt;setField($add);

                        //如果上链有数据了就增加余额
                        M('member')-&gt;where(['id'=&gt;$payorder['uid']])-&gt;setInc('balance',$payorder['amount']);

                        //返回
                	$return['sign'] = true;
                	$return['state'] = 1;
                	$return['message'] = '充值成功！';
                	return $return;exit;
                    }
                }else{
                    $return['sign'] = false;
        	    $return['message'] = '未发现订单！';
        	    return $return;
                }
            // }
        } 
}
[/php]





<!-- ##{"timestamp":1703128583}## -->