# Setup webdav

Run webdav server

## To forward OPTIONS requests and increase max file size
```
sudo docker cp webdav.bjornf.dev <proxy_container_id>:/etc/nginx/vhost.d
sudo docker cp webdav.bjornf.dev_location <proxy_container_id>:/etc/nginx/vhost.d
```
