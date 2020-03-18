## 安装和启动 Jenkins

使用如下命令启动 Jenkins 容器(这里使用了中文定制版 Jenkins)：

`docker run -u root \
    -v /var/jenkins/data:/var/jenkins_home \
    -p 8080:8080 \
    jenkinszh/jenkins-zh:lts`{{execute}}