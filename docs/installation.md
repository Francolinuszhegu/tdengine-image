# TDengine部署指南

## ‌一、环境准备
### 系统配置
> -  服务器：鲲鹏服务器
> -  操作系统：Huawei Cloud EulerOS 2.0 64bit 
> - CPU: 2vCPUs 或更高
> - RAM: 4GB 或更大
> - Disk: 至少 40GrB

## ‌二、安装部署部署

### 1.安装docker
参考：[安装Docker](https://support.huaweicloud.com/bestpractice-hce/hce_bp_0002.html)

### 2.拉取官方镜像
```bash
docker pull tdengine/tdengine:latest
```
### 3.‌创建数据目录
```bash
mkdir -p /data/taos/data /data/taos/log
chmod 777 /data/taos
```

### 4.容器启动
```bash
docker run -d --name tdengine \
  -p 6030:6030 -p 6041:6041 -p 6043-6049:6043-6049 \
  -v /data/taos/data:/var/lib/taos \
  -v /data/taos/log:/var/log/taos \
  -e TAOS_ADAPTER_ENABLED=true \
  --restart=always \
  tdengine/tdengine:latest
```
