# Docker for Ubuntu

## 运行第一个容器

`docker info`


运行一个容器，命名web, *-i*: STDIN开启，*-t*: 分配伪tty终端<br>
`docker run --name web -i -t ubuntu /bin/bash`

进入Docker Shell 可以查看相关命令

- 检查主机名<br>
`cat /etc/hosts`       

- 检查的进程<br>
`ps -aux`


`docker ps -a`

`docker start yourcontainername`

`docker attach yourcontainername`
