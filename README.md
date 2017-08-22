1. 创建镜像：docker build -t registry_url/namespace/csphere/centos:7.1 DockerfilePath
2. 创建并启动容器：docker run -t -i --name containername imagename /bin/bash
3. 查看当前镜像：docker images
4. 查看容器：docker ps -a
5. 进入容器：docker exec -it containername /bin/bash
6. 启动容器：sudo docker start containername
7. 停止容器：sudo docker stop containername
