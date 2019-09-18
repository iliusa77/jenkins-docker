# jenkins-docker

```
    git clone https://github.com/iliaeriomenco/jenkins-docker.git
    cd jenkins-docker/master
    docker build -t jenkins-master .
    cd ../slave
    docker build -t jenkins-slave .
    docker-compose -f .\docker-compose.ci.yml up
```
