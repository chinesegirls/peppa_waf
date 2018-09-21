# peppa_waf
一个练手的waf，就叫佩奇吧， an open source waf  (Web Application Firewalls)  base on tengine

# yum install pcre pcre-devel openssl openssl-devel

# cd LuaJIT-2.1.0 && make && make install

先安装 luajit

然后安装tengine

./configure --prefix=/usr/local/nginx --with-http_lua_module --with-luajit-lib=/usr/local/lib/ --with-luajit-inc=/usr/local/include/luajit-2.1/ --with-lua-inc=/usr/local/include/luajit-2.1/ 

make && make install