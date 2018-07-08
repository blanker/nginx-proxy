# nginx反向代理简单演示
nginx-1.conf和nginx-2.conf是普通的web服务器
nginx-3.conf配置成反向代理

```bash
nginx -c nginx-3.conf -t # 检查配置文件
nginx -c nginx-3.confg -s reload # 重新载入配置文件
```

