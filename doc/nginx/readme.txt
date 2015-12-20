sudo nginx
sudo nginx -s stop
sudo nginx -s quit	
sudo nginx -s reload

# mdfind nginx.conf
conf-path=/usr/local/etc/nginx/nginx.conf
http-log-path=/usr/local/var/log/nginx/access.log
error-log-path=/usr/local/var/log/nginx/error.log 

# 测试是否成功开启
curl -I -H "Accept-Encoding: gzip, deflate" "http://qihua.com/Qihua/gift"
curl -I -H "Accept-Encoding: gzip, deflate" "http://qihua.com/Qihua/resources/lib/jquery/plugins/flexslider/jquery.flexslider.css"
curl -I -H "Accept-Encoding: gzip, deflate" "http://qihua.com/Qihua/resources/images/product/placeholder.gif"
curl -I -H "Accept-Encoding: gzip, deflate" "http://qihua.com/Qihua/resources/lib/jquery/plugins/flexslider/jquery.flexslider.js"