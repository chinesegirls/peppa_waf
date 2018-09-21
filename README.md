# peppa_waf ：

#### an open source waf (Web Application Firewalls) base on Tengine-2.2.2 and luajit2.1.0，jemalloc-5.1.0
一个练手的waf，就叫peppa_waf吧

#sudo apt-get install libpcre3 libpcre3-dev openssl wget libssl-dev

#yum install pcre pcre-devel openssl openssl-devel zlib-devel wget

#cd lua && make && make install

#cd /usr/local/src && wget https://github.com/jemalloc/jemalloc/releases/download/5.1.0/jemalloc-5.1.0.tar.bz2 && tar xvf jemalloc-5.1.0.tar.bz2 && cd jemalloc-5.1.0 && ./configure --prefix=/usr/local/jemalloc && make && make install



#echo "/usr/local/lib" >> /etc/ld.so.conf

#ldconfig

先安装 luajit

然后安装tengine

#./configure --prefix=/usr/local/nginx --with-jemalloc=/usr/local/src/jemalloc-5.1.0 --with-http_lua_module --with-luajit-lib=/usr/local/lib/ --with-luajit-inc=/usr/local/include/luajit-2.1/ --with-lua-inc=/usr/local/include/luajit-2.1/ 

#make && make install
