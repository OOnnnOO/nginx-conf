# nginx 配置文件

## git创建独立的新分支

```sh
git checkout --orphan newBranch
```

## 生成默认证书

```sh
sudo openssl req -x509 -nodes -days 365 -newkey rsa:2048 \
-keyout /usr/local/nginx/conf.d/key/default.key \
-out /usr/local/nginx/conf.d/key/default.crt
```
