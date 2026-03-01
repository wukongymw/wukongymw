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

修复更新升级版本，会员投稿互换的 ，没有搭建 忘记截图了 ，看过演示网站是正常没问题的。具体大家自己可研究

centos7.6

安装宝塔

yum install -y wget &amp;&amp; wget -O install.sh http://download.bt.cn/install/install_6.0.sh &amp;&amp; sh install.sh

Nginx 1.2

mysql8.0

PHP7.2 Redis扩展

supervisor

PHP禁用函数全部删除

网站运行目录/public

安装：supervisor

yum -y install supervisor

配置supervisor：

/etc/supervisord.conf

将files = relative/directory/*.ini改为files = /www/wwwroot/ebite/supervisor/*.conf

命令

supervisord -c /etc/supervisord.conf

supervisorctl restart all

伪静态：laravel5

nginx websocket端口转发配置：

location /ws {

proxy_pass http://127.0.0.1:7272;

proxy_http_version 1.1;

proxy_set_header X-Forwarded-For

$proxy_add_x_forwarded_for;

proxy_set_header Upgrade $http_upgrade;

proxy_set_header Connection "Upgrade";

proxy_set_header X-Real-IP $remote_addr;

rewrite /ws/(.*) /$1 break;

proxy_redirect off;

}

172.17.0.1

常用命令

supervisorctl status

supervisorctl stop ispec

supervisorctl start ispec

supervisorctl restart ispec

supervisorctl reread

supervisorctl update

supervisorctl reload

/usr/bin/python /usr/bin/supervisord -c /etc/supervisord.conf

<a href="https://cdn.wukongymw.com/wp-content/uploads/2023/03/1677917868-d865964f6481287.jpg"><img src="https://cdn.wukongymw.com/wp-content/uploads/2023/03/1677917868-d865964f6481287.jpg" width="861" height="561" class="aligncenter size-full wp-image-198450" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2023/03/1677917867-75675163e34bbfe.jpg"><img src="https://cdn.wukongymw.com/wp-content/uploads/2023/03/1677917867-75675163e34bbfe.jpg" width="1280" height="582" class="aligncenter size-full wp-image-198449" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2023/03/1677917866-a5719f1b5a9c380.jpg"><img src="https://cdn.wukongymw.com/wp-content/uploads/2023/03/1677917866-a5719f1b5a9c380.jpg" width="1280" height="602" class="aligncenter size-full wp-image-198448" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<!-- ##{"timestamp":1677946766}## -->