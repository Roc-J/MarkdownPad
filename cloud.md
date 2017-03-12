# 云计算 #
多领域的现代化基线  
* AWS  
* Azure  
* Aliyun  

## 计算与存储 ##  

**技术组成**

### 存储 ###
存储分层  
Block  
* 支持Read/Write等少量操作  
* 以扇区读写单位  
* /dev/sda Linux  
* 本地  or 网络  
* EBS不开源 可以作为一个服务来用

Object  
* 支持key-Object的操作 Get Put Post  
* GFS  
* HDFS  
* Ceph  
* S3  

Filesystem 
* 系统调用  
* 支持大量文件系统操作  
* Metadata 和Data 分离 

### 硬件虚拟化 ###

### 操系统虚拟化 ###

### 容器技术 ###

unikernel 

serverless(Function as a service)

### 计算类型 ###

### 网络 ###

Classic VS VPC  

* SDN  
* Classic  
* VPC  
* OpenFlow


## 云原生应用 ##

### Docker ###

### Control Group ###

### 基础架构容器化 ###

### 微服务介绍 ###

单体模式 --> 微服务

scale cub


12-Factor  
* 基准代码：一份基准代码，多份部署     
* 依赖  
* 配置  
* 后端服务  
* 构建，发布和运行   
* 进程   
* 端口绑定  
* 并发  
* 易处理  
