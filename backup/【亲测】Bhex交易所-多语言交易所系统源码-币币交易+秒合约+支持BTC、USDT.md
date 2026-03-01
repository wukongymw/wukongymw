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
<div id="sc_fankui">测试反馈</div>
测试环境：宝塔、Linux系统、PHP7.2、MySQL5.6，根目录public，伪静态larvael5，PHP需安装扩展：fileinfo、memcache、Redis、imap、intl、exif、xsl，PHP要删除全部禁用函数

由于k线环境比较复杂，我就没有安装了，你们自己搞一下，这一套有PC+WAP端，都是vue编译后，也是前几年的产品，没什么新意

修改.env里面的域名、数据库信息、服务器ip

在public下面全局搜索 jyis.timibbs.vip 替换为自己的域名

后台：/admin
账号：admin
密码：123456

下面是K线环境安装教程：

交易所K线需要用到的工具
liunx系统

java - jdk1.8

JAVA安装
https://www.cnblogs.com/wjup/p/11041274.html

输入 java -version 可以查看
vi /etc/profile这个文件的地方加指向进去就可以

JAVA_HOME=/usr/lib/jvm/jre-1.6.0-openjdk.x86_64
PATH=$PATH:$JAVA_HOME/bin
CLASSPATH=.:$JAVA_HOME/lib/dt.jar:$JAVA_HOME/lib/tools.jar
export JAVA_HOME CLASSPATH PATH

填写保存 终端输入 . /etc/profile

java 安装完成

elasticsearch安装
https://www.cnblogs.com/socketqiang/p/11363024.html

先下载 wget https://artifacts.elastic.co/downloads/elasticsearch/elasticsearch-6.6.0.tar.gz

下载完成输入
tar -zxvf elasticsearch-6.6.0.tar.gz

解压得到包装包 改下名字
然后复制到这里 /usr/local
进入到es安装目录下的config文件夹中，修改elasticsearch.yml 文件

#配置es的集群名称，默认是elasticsearch，es会自动发现在同一网段下的es，如果在同一网段下有多个集群，就可以用这个属性来区分不同的集群。
cluster.name: my-es
#节点名称
node.name: node-1
#设置索引数据的存储路径
path.data: /usr/local/elasticsearch/data
#设置日志的存储路径
path.logs: /usr/local/elasticsearch/logs
#设置当前的ip地址,通过指定相同网段的其他节点会加入该集群中
network.host: 0.0.0.0
#设置对外服务的http端口
http.port: 9200
#设置集群中master节点的初始列表，可以通过这些节点来自动发现新加入集群的节点
discovery.zen.ping.unicast.hosts: ["127.0.0.1","10.10.10.34:9200"]

一定要记得在es根目录创建一个目录 data

useradd es
passwd es
密码随便输入
目录权限 　chown -R es:es /usr/local/elasticsearch

已经改变了
现在所有的都安装完成了
下面有带报错的,我们一块处理了
vi /etc/security/limits.conf这个文件加
* soft nofile 65536
* hard nofile 131072
vi /etc/sysctl.conf 这个也要
vm.max_map_count=655360
执行 sysctl -p

现在启动下
先进入文件所在/usr/local/elasticsearch/bin
点开宝塔自带终端
输入 su es

启动命令 sh elasticsearch -d
9300 9200
这两个端口如果没有显示正常那就是没有启动成功
有报错,我们处理下

脚本：
宝塔脚本按需要上，时间自调
php artisan get_kline_data_fivemin
cd /www/wwwroot/exchange4008.ex
php artisan get_kline_data_fivemin

php artisan get_kline_data_fifteenmin
cd /www/wwwroot/exchange4008.ex
php artisan get_kline_data_fifteenmin

php artisan get_kline_data_thirtymin
cd /www/wwwroot/exchange4008.ex
php artisan get_kline_data_thirtymin

php artisan get_kline_data_monthly
cd /www/wwwroot/exchange4008.ex
php artisan get_kline_data_monthly

php artisan get_kline_data_hourly
cd /www/wwwroot/exchange4008.ex
php artisan get_kline_data_hourly

php artisan get_kline_data_daily
cd /www/wwwroot/exchange4008.ex
php artisan get_kline_data_daily

php artisan get_kline_data_weekly
cd /www/wwwroot/exchange4008.ex
php artisan get_kline_data_weekly

php artisan auto_change start
cd /www/wwwroot/exchange4008.ex
php artisan auto_change start

php artisan queue:work
cd /www/wwwroot/exchange4008.ex
php artisan queue:work

php artisan schedule:run websocket-client
cd /www/wwwroot/exchange4008.ex
php artisan schedule:run websocket-client

php artisan websocket:client restart
cd /www/wwwroot/exchange4008.ex
php artisan websocket:client restart

php start.php start
cd /www/wwwroot/exchange4008.ex/public/vendor/webmsgsender
php start.php start

续签Let's Encrypt证书
/www/server/panel/pyenv/bin/python -u /www/server/panel/class/acme_v2.py --renew=1
<div id="sc_jietu">截图展示</div>
<a href="https://cdn.wukongymw.com/wp-content/uploads/2023/10/1696945888-46afbf758ea559f.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2023/10/1696945888-46afbf758ea559f.png" width="359" height="770" class="aligncenter size-full wp-image-200422" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2023/10/1696945886-dc10930e84a9411.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2023/10/1696945886-dc10930e84a9411.png" width="359" height="770" class="aligncenter size-full wp-image-200421" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2023/10/1696945885-1cf10dca2071c10.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2023/10/1696945885-1cf10dca2071c10.png" width="359" height="770" class="aligncenter size-full wp-image-200420" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2023/10/1696945883-e20dd8ace595abb.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2023/10/1696945883-e20dd8ace595abb.png" width="359" height="770" class="aligncenter size-full wp-image-200419" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2023/10/1696945880-0c4741babc429bf.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2023/10/1696945880-0c4741babc429bf.png" width="1920" height="3021" class="aligncenter size-full wp-image-200418" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2023/10/1696945873-4ea7cabe78dc839.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2023/10/1696945873-4ea7cabe78dc839.png" width="1920" height="885" class="aligncenter size-full wp-image-200417" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<a href="https://cdn.wukongymw.com/wp-content/uploads/2023/10/1696945870-fd174728223ab53.png"><img src="https://cdn.wukongymw.com/wp-content/uploads/2023/10/1696945870-fd174728223ab53.png" width="1920" height="885" class="aligncenter size-full wp-image-200416" style="border-radius:12px; padding:5px; display:block; clear:both; margin:0 auto;"></a>

<!-- ##{"timestamp":1696975361}## -->