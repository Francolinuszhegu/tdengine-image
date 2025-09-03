 <h1 align="center">TDengine Database</h1>
  <p align="center">
    <strong>English</strong> | <a href="README.md"><strong>Simplified Chinese</strong></a>
  </p>


## Table of Contents

- [Repository Introduction](#project-introduction)
- [Prerequisites](#prerequisites)
- [Image Description](#image-description)
- [Get Help](#get-help)
- [How to Contribute](#how-to-contribute)

## Project Introduction

[TDengine](https://github.com/memcached/memcached) is an open-source, high-performance, cloud-native Time Series Database (TSDB), specifically optimized for scenarios such as the Internet of Things (IoT), Connected Vehicles, Industrial Internet, finance, and IT operation and maintenance. It also comes with built-in system functions like caching, stream computing, and data subscription, which can significantly reduce the complexity of system design and lower R&D and operational costs. It is a minimalist time-series data processing platform. This product provides out-of-the-box TDengine based on the Huawei Cloud EulerOS 2.0 64-bit system for Kunpeng servers.

## Core Features

- **Integrated Design**: Integrates modules such as message queue, cache, and stream computing, providing full-stack data processing capabilities without the need to integrate additional components like Kafka and Spark;
- **Performance**: Compared with general database technologies, TDengine can process millions of requests per second, with performance improved by more than 10 times. In the TSBS benchmark test, its write performance, query performance, and storage efficiency are all better than InfluxDB and TimescaleDB.

The open-source image product [**TDengine Database**](https://marketplace.huaweicloud.com/hidden/contents/19146527-8825-4046-ae72-d6856cf22d10#productid=OFFI1166672139135340544) provided by this project has pre-installed TDengine version 3.3.3.0 and its related operating environment, and offers deployment templates. Follow the user guide to easily start the efficient "out-of-the-box" experience.


> **System Requirements:**
> - CPU: 2vCPUs or higher
> - RAM: 4GB or larger
> - Disk: At least 40GB

## Prerequisites
[Register a Huawei account and activate Huawei Cloud](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## Image Description

| Image Specification                                                                                                 | Feature Description | Remarks |
|------------------------------------------------------------------------------------------------------------------| --- | --- |
| [TDengine-3.3.3.0-kunpeng](https://github.com/HuaweiCloudDeveloper/tdengine-image/tree/TDengine-3.3.3.0-kunpeng) | Installed and deployed based on Kunpeng server + Huawei Cloud EulerOS 2.0 64bit |  |

## Get Help
- For more questions, you can contact us through [issue](https://github.com/HuaweiCloudDeveloper/tdengine-image/issues) or the service support of the specified product in the Huawei Cloud Marketplace
- For other open-source images, please refer to [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos)

## How to Contribute
- Fork this repository and submit a pull request
- Synchronously update README.md based on your open-source image information