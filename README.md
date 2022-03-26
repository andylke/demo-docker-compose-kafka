`docker-compose up -d`

```
[+] Running 15/15
 - zookeeper Pulled                                                               66.2s
   - 131f1a26eef0 Pull complete                                                   12.5s
   - 16b78ed2e822 Pull complete                                                   12.8s
   - f7352f1ba78a Pull complete                                                   57.0s
   - 3a498372ace6 Pull complete                                                   57.9s
   - 2ea0fca7e4a4 Pull complete                                                   58.0s
   - c33c6c0781fc Pull complete                                                   58.1s
   - 5d9855bac5a8 Pull complete                                                   61.3s
   - 083e1d04595f Pull complete                                                   61.4s
 - kafka Pulled                                                                   66.2s
   - e7233e20a08e Pull complete                                                   56.6s
   - 9b9cbc4e490c Pull complete                                                   56.9s
   - e06c925589f1 Pull complete                                                   57.9s
   - 45f1197956c6 Pull complete                                                   61.3s
   - 1dcef6fb6396 Pull complete                                                   61.5s
[+] Running 3/3
 - Network demo-docker-compose-kafka_default        Created                        0.1s
 - Container demo-docker-compose-kafka-zookeeper-1  Started                        1.1s
 - Container demo-docker-compose-kafka-kafka-1      Started                        1.5s

```

`docker-compose down`

```
[+] Running 3/3
 - Container demo-docker-compose-kafka-kafka-1      Removed                        6.1s
 - Container demo-docker-compose-kafka-zookeeper-1  Removed                        0.8s
 - Network demo-docker-compose-kafka_default        Removed                        0.2s
```
