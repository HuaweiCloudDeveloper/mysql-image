# Mysql部署指南

## ‌一、环境准备

### 一、更新系统

```bash
yum -y update  
yum -y upgrade
```

## ‌二、安装docker

参考：[安装Docker](https://support.huaweicloud.com/bestpractice-hce/hce_bp_0002.html)


## 三、拉取镜像和创建容器

### 1.拉取镜像
```bash
docker pull mysql:8.0
```

### 2.创建容器
```bash
docker run -d \
   --name mysql \
   -e MYSQL_ROOT_PASSWORD=123456 \
   -p 3306:3306 \
   -v /opt/mysql/data:/var/lib/mysql \
   -v /opt/mysql/conf:/etc/mysql/conf.d \
   --restart always \
   mysql:8.0
```


