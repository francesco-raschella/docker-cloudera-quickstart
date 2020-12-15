# docker-cloudera-quickstart

STEP 1:
docker pull cloudera/quickstart:latest

STEP 2:
docker run --hostname=quickstart.cloudera --privileged=true -t -i -p 8888:8888 -p 80:80 cloudera/quickstart /usr/bin/docker-quickstart

STEP 3:
browse hue localhost:8888
Optionally start services
