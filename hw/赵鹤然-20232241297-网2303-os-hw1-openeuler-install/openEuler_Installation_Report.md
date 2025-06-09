# openEuler 安装报告

## 1. 准备工作

### 下载 VirtualBox

访问 VirtualBox 官网(https://www.virtualbox.org/wiki/Downloads)， 下载 Windows hosts 版本

### 安装 openEuler 镜像

访问 openEuler 官网(https://www.openeuler.org/zh/)， 下载openEuler 24.03 LTS SP1（最新）的ISO 镜像文件，我选择下载Offline Standard ISO的软件包类型

## 2. 创建与配置虚拟机

### 打开 VirtualBox

启动 VirtualBox，点击“新建”按钮创建虚拟机

### 配置虚拟机

- 名称：oe
- 文件夹：D:\openEuler
- 类型：Linux
- 版本：Other Linux (64-bit)
- 内存大小：2048 MB
- 处理器：4
- 硬盘：选择“现在创建虚拟硬盘”，分配 20GB 储存空间
  
  ### 挂载 ISO 镜像
  
  在虚拟机设置中，选择“存储”选项，点击“控制器: IDE”下的光盘图标，选择“选择虚拟光盘文件”，加载下载好的 openEuler ISO 镜像

## 3. 安装 openEuler

- 设置语言支持：简体中文  
- 选择安装目的地，选择sda  
- 设置 root 密码并完成安装，等待安装完毕后重启系统  
- 去除镜像光驱，重启登录 