wget --no-check-certificate https://raw.githubusercontent.com/ZZMHA/shadowsocks_install/master/shadowsocks-all.sh
chmod +x shadowsocks-all.sh       

./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log


卸载   ./shadowsocks-all.sh uninstall
启动脚本后面的参数含义，从左至右依次为：启动，停止，重启，查看状态。

Shadowsocks-Python 版：

/etc/init.d/shadowsocks-python start | stop | restart | status

ShadowsocksR 版：

/etc/init.d/shadowsocks-r start | stop | restart | status

Shadowsocks-Go 版：

/etc/init.d/shadowsocks-go start | stop | restart | status

Shadowsocks-libev 版：

/etc/init.d/shadowsocks-libev start | stop | restart | status

各版本默认配置文件

Shadowsocks-Python 版：

/etc/shadowsocks-python/config.json

ShadowsocksR 版：

/etc/shadowsocks-r/config.json

Shadowsocks-Go 版：

/etc/shadowsocks-go/config.json

Shadowsocks-libev 版：

/etc/shadowsocks-libev/config.json
