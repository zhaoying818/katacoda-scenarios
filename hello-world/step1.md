1.使用如下命令启动 Jenkins 容器(这里使用了中文定制版 Jenkins)：

`docker run -d -p 8080:8080 --name jenkins jenkinszh/jenkins-zh:lts`{{execute}}

2.你可以通过下面 URL 打开 Jenkins Dashboard：
`https://[[HOST_SUBDOMAIN]]-8080-[[KATACODA_HOST]].environments.katacoda.com/`{{open}}

3.通过管理员密码解锁 Jenkins
`docker exec -it jenkins /bin/bash -c "cat /var/jenkins_home/secrets/initialAdminPassword"`{{execute}}
命令的执行结果就是步骤2的所需的管理员密码

4.根据安装向导，完成jenkins的配置。