## 安装和启动 Jenkins

1.使用如下命令启动 Jenkins 容器(这里使用了中文定制版 Jenkins)：

`docker run -d -p 8080:8080 jenkinszh/jenkins-zh:lts`{{execute}}

2.你可以通过下面 URL 打开 Jenkins Dashboard：
`https://[[HOST_SUBDOMAIN]]-8080-[[KATACODA_HOST]].environments.katacoda.com/`{{open}}

用户名是：`admin`{{copy}}，密码是：`9YxwvCOUPML8onXF`{{copy}}

3.Jenkins 可能需要一点时间来完成启动并准备就绪，在接下来的步骤中，您将使用 Dashboard 开始构建 Maven 项目。