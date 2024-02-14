#### 利用docker部署

1. 下载docker镜像

```bash
docker pull benshellx/tts_azure:latest
```

2. 运行容器

```bash
docker run -itd \
           --name tts \
            -p 3035:3035 \
           --restart=always \
           zengsuyi/tts:latest
```

3. 访问地址

```bash
http://ip:3035/
```
