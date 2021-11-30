# jenkins-centos-app-build-qr-code


> 一个可以让jenkins app 打包生成二维码下载地址的项目

![image](https://user-images.githubusercontent.com/19643260/144008397-99618744-4977-4920-9f97-9a3903f12971.png)


[镜像地址](https://registry.hub.docker.com/repository/docker/liyinchi/jenkins-centos-app-build-qr-code)


### 拉取镜像

```
docker pull liyinchi/jenkins-centos-app-build-qr-code:1.0.0
```

### 启动容器
```
docker run -d --name jenkins-app -p 50000:50000 -p 8001:83 -p 8000:8000 liyinchi/jenkins-centos-app-build-qr-code:1.0.0
```


### 访问jenkins

>http:127.0.0.1:8000

### 触发构建项目

### 查看生成的app下载地址和二维码
