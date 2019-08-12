# double_master_mysql
MySQL双主集群

## 注意
这是部署mysql-5.7.20版本的mysql服务,是双主集群部署,由于安装包太大,所以需要自行下载安装包,下方给出安装包版本和存放位置

## 安装包下载地址
链接：https://pan.baidu.com/s/165v5mRPKbOEhGcuQx8NaXw 
提取码：nabm 

## 使用方式
- 在role/mysql目录下创建file目录
- 将mysql5.7的包放到file目录下
- 根据包的版本和修改参数信息
- 执行 ansible-playbook -i hosts site.yml
