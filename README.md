# php 练习

## localhost/127.0.0.1 无法访问
#### 运行 sudo apachectl start 命令后 apache 已被启动, 但是在浏览器中输入 localhost 或 127.0.0.1, 页面无法访问.
#### 修改 /private/etc/apache2/httpd.conf 文件中默认端口 80 为 8000, 浏览器输入时带上端口号仍无法访问.
#### 后在网页 https://segmentfault.com/q/1010000010178746 中的方法, 运行命令 python -m SimpleHTTPServer 8000, 可以正常访问. 但不知道原因, 询问了答案提供者, 等待回复中...
