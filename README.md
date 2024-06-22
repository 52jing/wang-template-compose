<h4 align="right"><strong>English</strong> | <a href="./README_zh.md">简体中文</a></h4>

# Wang Template Compose

## Introduction

This project is for the rapid deployment of the WangTemplate report rendering platform.

Frontend Repository:

- Github: [https://github.com/52jing/wang-template-admin](https://github.com/52jing/wang-template-admin)
- Gitee: [https://gitee.com/i52jing/wang-template-admin](https://gitee.com/i52jing/wang-template-admin)

Backend Repository:

- Github: [https://github.com/52jing/wang-template-backend](https://github.com/52jing/wang-template-backend)
- Gitee: [https://gitee.com/i52jing/wang-template-backend](https://gitee.com/i52jing/wang-template-backend)

## Preparation

Please install Docker and Docker Compose first.

## Configuration

You can change the backend config file at `backend/config/application-prod.yml` and Nginx config file at `nginx/server.conf`.

## Start

```
docker-compose up -d
```

Request `http://localhost:8500` 。
