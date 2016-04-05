# Docker和PaaS的基础分享

## docker基本应用

    docker --help
    
![image](https://github.com/wangyapu0714/my_post/raw/master/md_pic/docker/docker_command.png)


## docker镜像与docker文件系统

镜像是docker的灵魂所在，也是软件交付的产品。

![image](https://github.com/wangyapu0714/my_post/raw/master/md_pic/docker/docker_system.png)


    FROM ubuntu:14.04
    ADD start.sh /
    VOLUME /data
    CMD ["./start.sh"]


## cgroup、namespace与docker（具体见上次分享）

[go与docker分享](http://wangyapu0714.github.io/2016/01/28/go_docker_share/)


## PaaS架构设计




## Docker结合Jenkins的思路

