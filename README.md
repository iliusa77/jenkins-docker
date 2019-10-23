## jenkins-docker

### Installation and run
```
    git clone https://github.com/iliusa77/jenkins-docker.git
    cd jenkins-docker/master
    docker build -t jenkins-master .
    cd ../slave
    docker build -t jenkins-slave .
    docker-compose -f docker-compose-ci.yml up
```

### Open in browser

http://ip:8080

username: admin

password: Einohng6
