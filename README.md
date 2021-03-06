# docker
The docker repository contains several subprojects resulting in docker images. All images can be found on Docker Hub https://hub.docker.com/u/cemmersb/

## Image Overview
| Repository  |Tag    | Latest | Description                   |
|-------------|-------|--------|-------------------------------|
| activemq5   | 0.0.3 | x      | ActiveMQ 5.12.1 on CentOS     |
| activemq5   | 0.0.2 |        | ActiveMQ 5.12.1 on CentOS     |
| activemq5   | 0.0.1 |        | ActiveMQ 5.12.1 on CentOS     |
| centos-jdk8 | 1.0.1 | x      | JDK8 update 65, b17 on CentOS |
| centos-jdk8 | 1.0.0 |        | JDK8 update 65, b17 on CentOS |
| centos-jdk7 | 1.0.0 | x      | JDK7 update 79, b15 on CentOS |

## Run: activemq5
```
$ docker pull cemmersb/activemq5
$ docker run -i -t -p=61616:61616 -p=8161:8161 -d --name=activemq_1 cemmersb/activemq5 /bin/bash
```

## Run: centos-jdk8
```
$ docker pull cemmersb/centos-jdk8
$ docker run -i -t cemmersb/centos-jdk8 bash
``` 

## Run: centos-jdk7
```
$ docker pull cemmersb/centos-jdk7
$ docker run -i -t cemmersb/centos-jdk7 bash
```
