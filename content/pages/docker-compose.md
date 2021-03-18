---
title: docker-compose 
---

# Install newer version 

[Ref](https://www.smarthomebeginner.com/synology-docker-media-server/)

1. Install docker package
2. back up


      sudo su
      cd /var/packages/Docker/target/usr/bin/
      mv docker-compose docker-compose_bak
      
4. Curl 

      curl -L https://github.com/docker/compose/releases/download/X.XX.X/docker-compose-`uname -s`-`uname -m` -o docker-compose
      
      After browser docker/compose/release
      
      use the latest version 
 
 5. follow the guide
