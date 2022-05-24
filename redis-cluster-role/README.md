# ansible-redis

#### 介绍
ansible-playbook 自动部署redis集群（主从+哨兵）

#### 软件架构
软件架构说明


#### 安装教程

git克隆到ansible主控机
主控机到redis服务器免密

#### 使用说明

1. 进入工程目录，修改hosts配置文件，填入服务器IP及全局变量
2. 根据实际安装修改redis.yml文件中相关目录，common 为安装redis及redis依赖库，测试时哨兵和主从在同一台机器因此只安装一个redis，若哨兵和主从在不同机器上，hosts此处填写all。并根据服务器自身需要修改工作目录及日志目录

