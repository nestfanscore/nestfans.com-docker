Homeland Docker
-----------------

[Homeland](http://gethomeland.com) 基于 Docker 的自动化部署方案。

## 系统需求

- Linux Server [4 Core CPU, 4G Memory, 50G Disk, 64 位] - _建议 Ubuntu Server 14.04_
- [Docker](https://www.docker.com/), [Docker Compose](https://docs.docker.com/compose/)
- [Aliyun OSS](https://www.aliyun.com/product/oss) 或 [UpYun](https://www.upyun.com) 用于文件存储。


## Usage
### 安装 Docker:
下面的脚本是针对 Ubuntu Server 14.04 设计的，其他版本，请查阅 Docker 官方的安装文档。

curl -sSL https://git.io/install-docker | bash
测试是否安装成功：

```bash
sudo docker info
sudo docker-compose version
```

获取 nestfans.com 的项目

```bash
git clone https://github.com/nestfanscore/nestfans.com-docker.git
cd nestfans.com-docker/
```

## 其他使用说明

http://gethomeland.com/install/
