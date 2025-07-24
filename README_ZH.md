<p align="center">
  <h1 align="center">Mysql数据库</h1>
  <p align="center">
    <a href="README.md"><strong>English</strong></a> | <strong>简体中文</strong>
  </p>

## 目录

- [仓库简介](#项目介绍)
- [前置条件](#前置条件)
- [镜像说明](#镜像说明)
- [获取帮助](#获取帮助)
- [如何贡献](#如何贡献)

## 项目介绍
[Mysql](https://github.com/mysql/mysql-server) 是全球最广泛使用的开源关系型数据库管理系统（RDBMS）之一，以其高性能、高可用性、灵活性和强大的社区支持，成为 Web 应用开发中不可或缺的核心组件。‌

### **核心功能：**

- **‌高性能：** 
  - 支持多线程架构，能够同时处理成千上万的连接请求。
  - 提供索引优化、查询缓存等机制，显著提升查询效率。
  - 可扩展性强，适用于 TB 级别的数据存储和读写操作，广泛应用于电商、社交平台等对性能要求较高的场景。
- **‌跨平台兼容‌：** 
  - 支持主流操作系统，包括 Windows、Linux、macOS 等，几乎可以在所有服务器环境中部署运行，具有良好的可移植性和适配能力。‌
- **丰富的数据类型支持‌：** 
  - 基础类型：整数（INT）、浮点数（FLOAT/DOUBLE）、字符串（CHAR/VARCHAR）。
  - 时间日期类型：DATE、DATETIME、TIMESTAMP。
  - 特殊类型：TEXT、BLOB、JSON 等，支持结构化与非结构化数据混合存储。
- **‌安全可靠：**
   - 用户权限管理：支持基于用户的账户、密码、访问控制。
   - 数据备份与恢复：可通过 mysqldump 工具进行全量或增量备份。
   - 支持事务处理（ACID 特性），确保数据一致性与完整性。
- **灵活的扩展能力：**
  - 主从复制（Master-Slave Replication）：实现读写分离，提高并发处理能力。
  - 集群部署（如 MySQL Cluster）：提供高可用性和负载均衡。
  - 存储引擎插件化：如 InnoDB（支持事务）、MyISAM（读取速度快）等，可根据业务需求灵活选择。
  


本项目提供的开源镜像商品 [**Mysql数据库**]() ，已预先安装Mysql及其相关运行环境，并提供部署模板。快来参照使用指南，轻松开启“开箱即用”的高效体验吧。

> **系统要求如下：**
> - CPU: 2GHz 或更高
> - RAM: 4GB 或更大
> - Disk: 至少 40GB

## 前置条件
[注册华为账号并开通华为云](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## 镜像说明

| 镜像规格                                                                                                  | 特性说明                                           | 备注 |
|-------------------------------------------------------------------------------------------------------|------------------------------------------------| --- |
| [Mysql-8.0-kunpeng](https://github.com/HuaweiCloudDeveloper/mysql-image/tree/Mysql-8.0-kunpeng) | 基于 鲲鹏服务器 + Huawei Cloud EulerOS 2.0 64bit 安装部署 |  |

## 获取帮助
- 更多问题可通过 [issue](https://github.com/HuaweiCloudDeveloper/mysql-image/issues) 或 华为云云商店指定商品的服务支持 与我们取得联系
- 其他开源镜像可看 [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos)

## 如何贡献
- Fork 此存储库并提交合并请求
- 基于您的开源镜像信息同步更新 README.md
