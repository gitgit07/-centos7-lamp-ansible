# -centos7-lamp-ansible
 使用Ansible Playbooks和Roles在多台CentOS 7.6服务器上自动化部署LAMP环境及网站应用

## 简介
# CentOS 7 LAMP Ansible Playbooks

本项目提供了一套Ansible Playbooks和Roles，用于在多台CentOS 7.6服务器上自动化部署LAMP环境（Linux, Apache, MySQL, PHP）以及安装和配置一个基础的网站应用。

这些脚本旨在简化和加速配置过程，确保在所有服务器上提供一致的环境设置。

## 特性

- **自动化部署**：快速在多台服务器上部署LAMP环境。
- **可定制**：易于修改以适应不同的配置需求。
- **幂等性**：多次执行相同的配置不会有不同的效果。
- **简洁的配置**：清晰的任务划分，易于理解和维护。

## 开始使用

### 前置条件

在开始之前，请确保您的控制节点已经安装了Ansible。您可以通过以下命令安装Ansible：


sudo yum install ansible
您还需要确保您有目标服务器的SSH访问权限，并且它们也安装了CentOS 7.6。

安装和配置
克隆仓库到您的控制节点：

git clone https://github.com/gitgit07/-centos7-lamp-ansible.git
cd centos7-lamp-ansible

参考readme.txt
根据您的环境编辑 inventory 文件，添加您的服务器地址。
自定义 group_vars 或 host_vars 目录下的变量文件，以满足您的配置需求。

运行Ansible Playbook



欢迎通过GitHub的Pull Requests或Issues来提交代码或报告问题。


