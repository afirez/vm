# ENV
- Vagrant ( Optional )
- VirtralBox ( Optional )
- Box matthias_reissner/ubuntu18_docker ( Optional )
- Docker ( Needed )

# CHANGELOG

## Vagrant

```
vagrant box
vagrant box list
vagrant box add matthias_reissner/ubuntu18_docker

vagrant 
vagrant status
vagrant init
vagrant up
vagrant ssh
vagrant halt

```

## Linux (ubuntu 18.04.2)

```

# find ...
find ~/aosp -name "*.java" |xargs grep "Zygote"

```

## docker

### android-jenkins


```
$ cd android-jenkins
$ sudo docker build -t afirezd/jenkins:1.1.0 .
$ sudo docker run -p 8080:8080 -p 50000:50000 -v /vagrant/jenkins:/var/jenkins_home afirezd/android-jenkins:1.1.0
$ docker run ps 
$ sudo docker exec ${container_id} cat /var/jenkins_home/secrets/initialAdminPassword
$ docker exec -it ${container_id} /bin/bash

```

### androidbuilder

```

$ cd androidbuilder
$ sudo docker build -t afirezd/androidbuilder:v1.0.0 .


```
