Linux 通过apt、yum等包管理器安装nginx后，使用此nginx.conf文件替换/etc/nginx/目录下的nginx文件，即可实现反向代理google

文件中 “sub_filter www.google.com  你的服务器IP;" 需要替换服务器IP

例如：        sub_filter www.google.com 123.124.125.126;
