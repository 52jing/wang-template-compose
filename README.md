# Wang Template Compose

## 说明

本项目用于快速部署 WangTemplate 报告生成平台。

## 准备

请先安装 Docker 及 Docker Compose。

## 配置

可修改后端服务配置 `backend/config/application-prod.yml` 及 Nginx 负载均衡配置 `nginx/server.conf`。

## 启动

```
docker-compose up -d
```

访问 `http://localhost:8500` 。
