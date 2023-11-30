# proxy

docker run -d  -p 23657:23657 -v /root/nginx/conf/nginx.conf:/etc/nginx/nginx.conf -v /root/nginx/conf/tcp.d/:/etc/nginx/tcp.d/ nginx
