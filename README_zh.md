<h4 align="right"><a href="./README.md">English</a> | <strong>简体中文</strong></h4>

# Wang Template Compose

## 说明

本项目用于快速部署 WangTemplate 报告生成平台。

前端地址：

- Github: [https://github.com/52jing/wang-template-admin](https://github.com/52jing/wang-template-admin)
- Gitee: [https://gitee.com/i52jing/wang-template-admin](https://gitee.com/i52jing/wang-template-admin)

后端地址：

- Github: [https://github.com/52jing/wang-template-backend](https://github.com/52jing/wang-template-backend)
- Gitee: [https://gitee.com/i52jing/wang-template-backend](https://gitee.com/i52jing/wang-template-backend)

## 准备

请先安装 Docker 及 Docker Compose。

## 配置

可修改后端服务配置 `backend/config/application-prod.yml` 及 Nginx 负载均衡配置 `nginx/server.conf`。

## 启动

```
docker-compose up -d
```

访问 `http://localhost:8500` 。
