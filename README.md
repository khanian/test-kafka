# test-kafka

1. Apache ZooKeeper 3.7.1 (latest stable release) //2023-03-24

![image](https://user-images.githubusercontent.com/13308117/227393350-d8051cab-3fab-48ca-aaa4-49bc1118139d.png)

2. download 후 압축을 푼다.
> tar -xvf ./apache-zookeeper-3.7.1-bin.tar.gz

3. cfg 파일 설정 변경
> cd ./apache-zookeeper-3.7.1-bin/conf

> cp ./zoo_sample.cfg zoo.cfg

> cd ..

> bin/zkServer.sh start

(window::JAVA_HOME 세팅 되어 있어야 함.)
> .\bin\zkServer.cmd     
