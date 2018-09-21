# peppa_waf ：

#### an open source waf (Web Application Firewalls) base on Tengine-2.2.2 and luajit2.1.0，jemalloc-5.1.0
一个练手的waf，就叫peppa_waf吧

#sudo apt-get install libpcre3 libpcre3-dev openssl libssl-dev

#yum install pcre pcre-devel openssl openssl-devel zlib-devel 

#cd lua && make && make install

#cd jemalloc && ./configure --prefix=/usr/local/jemalloc && make && make install


#echo "/usr/local/lib" >> /etc/ld.so.conf

#ldconfig

先安装 luajit

然后安装tengine

#./configure --prefix=/usr/local/nginx with-jemalloc=./jemalloc --with-http_lua_module --with-luajit-lib=/usr/local/lib/ --with-luajit-inc=/usr/local/include/luajit-2.1/ --with-lua-inc=/usr/local/include/luajit-2.1/ 

#make && make install
