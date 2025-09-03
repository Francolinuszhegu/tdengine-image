 <h1 align="center">TDengine数据库</h1>
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

[TDengine](https://github.com/memcached/memcached) 是一款 开源、高性能、云原生 的时序数据库（Time Series Database, TSDB）, 它专为物联网、车联网、工业互联网、金融、IT 运维等场景优化设计。同时它还带有内建的缓存、流式计算、数据订阅等系统功能，能大幅减少系统设计的复杂度，降低研发和运营成本，是一款极简的时序数据处理平台‌。本商品基于鲲鹏服务器的Huawei Cloud EulerOS 2.0 64bit系统，提供开箱即用的TDengine。

## 核心特性

- **‌一体化设计‌：** 集成了消息队列、缓存、流式计算等模块，提供全栈数据处理能力，无需集成Kafka、Spark等额外组件；
- **性能表现：** 相比通用数据库技术，TDengine每秒可处理数百万请求，性能提升10倍以上。在TSBS基准测试中，其写入性能、查询性能和存储效率均优于InfluxDB和TimescaleDB

本项目提供的开源镜像商品 [**TDengine数据库**](https://marketplace.huaweicloud.com/hidden/contents/19146527-8825-4046-ae72-d6856cf22d10#productid=OFFI1166672139135340544) 已预先安装3.3.3.0版本的TDengine及其相关运行环境，并提供部署模板。快来参照使用指南，轻松开启“开箱即用”的高效体验吧。


> **系统要求如下：**
> - CPU: 2vCPUs 或更高
> - RAM: 4GB 或更大
> - Disk: 至少 40GB

## 前置条件
[注册华为账号并开通华为云](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## 镜像说明

| 镜像规格                                                                                                             | 特性说明 | 备注 |
|------------------------------------------------------------------------------------------------------------------| --- | --- |
| [TDengine-3.3.3.0-kunpeng](https://github.com/HuaweiCloudDeveloper/tdengine-image/tree/TDengine-3.3.3.0-kunpeng) | 基于鲲鹏服务器 + Huawei Cloud EulerOS 2.0 64bit 安装部署 |  |

## 获取帮助
- 更多问题可通过 [issue](https://github.com/HuaweiCloudDeveloper/tdengine-image/issues) 或 华为云云商店指定商品的服务支持 与我们取得联系
- 其他开源镜像可看 [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos)

## 如何贡献
- Fork 此存储库并提交合并请求
- 基于您的开源镜像信息同步更新 README.md