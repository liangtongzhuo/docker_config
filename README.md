docker-compose up 

如果 redis 启动失败，可能是 redis 文件夹没有权限

```bash
$ chmod -R 777 ./docker-build/redis/data
```

## 