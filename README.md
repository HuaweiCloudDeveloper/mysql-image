<p align="center">
  <h1 align="center">Mysql Database</h1>
  <p align="center">
    <a href="README.md"><strong>English</strong></a> | <strong>简体中文</strong>
  </p>

## Table of Contents

- [Repository Introduction](#repository-introduction)
- [Prerequisites](#prerequisites)
- [Image Description](#image-description)
- [Get Help](#get-help)
- [How to Contribute](#how-to-contribute)

## Repository Introduction
[Mysql](https://github.com/mysql/mysql-server) is one of the world's most widely used open-source relational database management systems (RDBMS). With its high performance, high availability, flexibility, and strong community support, it has become an indispensable core component in web application development.

### **Core Features:**

- **High Performance:**
  - Supports a multi-threaded architecture, capable of handling thousands of connection requests simultaneously.
  - Provides mechanisms such as index optimization and query caching to significantly improve query efficiency.
  - Highly scalable, suitable for TB-level data storage and read/write operations, widely used in scenarios with high performance requirements such as e-commerce and social platforms.
- **Cross-platform Compatibility:**
  - Supports mainstream operating systems including Windows, Linux, macOS, etc., and can be deployed and run in almost all server environments, with good portability and adaptability.
- **Rich Data Type Support:**
  - Basic types: integers (INT), floating-point numbers (FLOAT/DOUBLE), strings (CHAR/VARCHAR).
  - Date and time types: DATE, DATETIME, TIMESTAMP.
  - Special types: TEXT, BLOB, JSON, etc., supporting mixed storage of structured and unstructured data.
- **Security and Reliability:**
  - User permission management: Supports user-based accounts, passwords, and access control.
  - Data backup and recovery: Full or incremental backups can be performed using the mysqldump tool.
  - Supports transaction processing (ACID properties) to ensure data consistency and integrity.
- **Flexible Scalability:**
  - Master-Slave Replication: Implements read-write separation to improve concurrent processing capabilities.
  - Cluster deployment (such as MySQL Cluster): Provides high availability and load balancing.
  - Plug-in storage engines: Such as InnoDB (supports transactions), MyISAM (fast reading speed), etc., which can be flexibly selected according to business needs.


The open-source image product [**Mysql Database**]() provided by this project has pre-installed Mysql and its related running environment, and provides deployment templates. Follow the user guide to easily start an efficient "out-of-the-box" experience.

> **System requirements are as follows:**
> - CPU: 2GHz or higher
> - RAM: 4GB or larger
> - Disk: At least 40GB

## Prerequisites
[Register a Huawei account and activate Huawei Cloud](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## Image Description

| Image Specification                                                                                     | Feature Description                                      | Remarks |
|-------------------------------------------------------------------------------------------------------|----------------------------------------------------------|---------|
| [Mysql-8.0-kunpeng](https://github.com/HuaweiCloudDeveloper/mysql-image/tree/Mysql-8.0-kunpeng) | Installed and deployed based on Kunpeng server + Huawei Cloud EulerOS 2.0 64bit |         |

## Get Help
- For more questions, you can contact us through [issue](https://github.com/HuaweiCloudDeveloper/mysql-image/issues) or the service support of the specified product in the Huawei Cloud Market.
- For other open-source images, please refer to [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos)

## How to Contribute
- Fork this repository and submit a pull request
- Synchronously update README.md based on your open-source image information