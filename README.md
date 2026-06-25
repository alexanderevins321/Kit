# This project is under development

<div align="center">
<p><a href="https://github.com/go-saas/kit" target="_blank"><img src="https://github.com/go-saas/kit/blob/main/docs/static/img/logo.png?raw=true" width="100"></a></p>
<span  style="font-weight: 800;font-size: 20px;">GO-SAAS-KIT </span> <span  style="font-weight: 800;font-size: 16px;">Starter kit for golang sass project</span>
<br> 
<a href="https://go-saas.github.io/kit/" target="_blank"><span  style="font-weight: 600;font-size: 18px;">docs</span></a>
<br>
</div>
Overview

![Overview](https://github.com/go-saas/kit/blob/main/docs/en-US/overview.png?raw=true)

# Architecture
![Architecture](https://github.com/go-saas/kit/blob/main/docs/static/img/go-saas-kit.drawio.png?raw=true)

# Demo 

address http://saas.nihaosaoya.com

- **Host** Username:admin  Password:123456


# Modules
* [x] User Management
* [x] Tenant Management, Tenant Plans and Subscription
* [x] Payments and Orders
* [x] Product Management


# Quick Start

### For Microservice

```
docker compose -f docker-compose.yml -f docker-compose.ms.yml -f docker-compose.kafka.yml -f docker-compose.tracing.yml up -d
```

Or with build
```
docker compose -f docker-compose.yml -f docker-compose.ms.yml -f docker-compose.kafka.yml  -f docker-compose.tracing.yml up -d --build
```

### Demo

Open `http://localhost:80` to see the web ui

Username: admin  
Password: 123456


# Development

```shell
make init
```
```shell
make all
```
```shell
make build
```

## Create New Service

```shell
kratos new <name> -r https://github.com/alexanderevins321/Kit
```



