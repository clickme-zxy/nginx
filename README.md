# nginx

[参考](https://www.cnblogs.com/luo630/p/9363478.html)

1. 安装

   * 安装指令

   ```java
   sudo apt-get install nginx
   ```

   * 文件
     * /usr/sbin/nginx:主程序
     * /etc/nginx:存放配置文件
     * /usr/share/nginx:存放静态文件
     * /var/log/nginx:存放日志

2. nginx常用指令

   * 查找nginx

     ```java
     whereis nginx
     ```

   * 查找当前运行的nginx进程：

     ```java
     ps -e|grep nginx
     ```

   * 访问nginx本地

     ```java
     127.0.0.1
     ```

   * 查看端口使用情况

     ```java
     netstat -ltunp
     ```

   * 杀死端口

     ```java
     sudo kill 端口号
     ```

   * 启动nginx

     ```java
     service nginx start
     ```

     ```java
     sudo nginx
     ```

     

   

   

