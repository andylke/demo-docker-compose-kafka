`docker-compose up -d`

```
[+] Running 3/3
 - Network demo-docker-compose-kafka_default        Created                               0.1s
 - Container demo-docker-compose-kafka-zookeeper-1  Started                               1.4s
 - Container demo-docker-compose-kafka-kafka-1      Started                               2.1s
```

`docker-compose down`

```
[+] Running 3/3
 - Container demo-docker-compose-kafka-kafka-1      Removed                               6.1s
 - Container demo-docker-compose-kafka-zookeeper-1  Removed                               0.8s
 - Network demo-docker-compose-kafka_default        Removed                               0.2s
```
