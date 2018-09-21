# peppa_waf ：

#### an open source waf (Web Application Firewalls) base on tengine

一个练手的waf，就叫佩奇吧

#sudo apt-get install libpcre3 libpcre3-dev openssl libssl-dev

#yum install pcre pcre-devel openssl openssl-devel zlib-devel 

#cd LuaJIT-2.1.0 && make && make install

先安装 luajit

然后安装tengine

./configure --prefix=/usr/local/nginx --with-http_lua_module --with-luajit-lib=/usr/local/lib/ --with-luajit-inc=/usr/local/include/luajit-2.1/ --with-lua-inc=/usr/local/include/luajit-2.1/ 

make && make install