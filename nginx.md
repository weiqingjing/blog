启动nginx nginx 所在目录

```nginx
/usr/local/Cellar/openresty/1.15.8.2/nginx/sbin/nginx
```



启动nginx 并且指定配置文件

```
/usr/local/Cellar/openresty/1.15.8.2/nginx/sbin/nginx -c /usr/local/etc/openresty/nginx.conf
```



查看nginx

```
ps -ef |grep nginx
```



重启nginx

```
/usr/local/Cellar/openresty/1.15.8.2/nginx/sbin/nginx -s reload /usr/local/etc/openresty/nginx.conf
```



停止nginx

```
pkill -9 nginx
```

