## 脚本来源于互联网，如有侵权请联系


### 准备工作

#### 1.一台国外服务器，如AWS,腾讯云等
#### 2.xshell
#### 3.SSR客户端

### 部署命令

#### 1.安装编译环境

```
yum install git gcc gcc-c++ make automake autoconf libtool pcre pcre-devel zlib zlib-devel openssl-devel wget vim -y
```

#### 2.下载部署脚本，并执行

```
wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubi/doubi/master/ssr.sh && chmod +x ssr.sh && bash ssr.sh
```

#### 3.根据实际情况进行安装
