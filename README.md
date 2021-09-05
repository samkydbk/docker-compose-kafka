# docker-compose-kafka
使用docker compose 搭建kafka集群 kafka+kafka-manage + zookeeper

### 创建自定义bridge网络
docker network create --subnet=172.18.0.0/16 netkafka

### docker网络操作常用命令
docker network ls
docker network inspect ID/NAME
docker network create
docker netowrk rm ID/NAME

### docker搭建kafka集群
![docker搭建kafka集群](https://user-images.githubusercontent.com/28728839/130782075-a6c26970-2c31-492b-aa57-52175b06eb9f.png "docker kafka集群")

### 查看zookeeper集群是否正常
![zookeeper](https://user-images.githubusercontent.com/28728839/130782334-1d9149a9-b7b0-4517-bd4b-95d1f0e00dcf.png "zookeeper")

### kafka管理ui界面 kafka manage ui
![kafka manage](https://user-images.githubusercontent.com/28728839/130782754-abe77373-edaf-4f90-bb60-ff01a78e40c2.png "kafka manage")


