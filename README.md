# linux
LINUX 学习资料
//防火墙配置
https://www.centos.bz/2017/12/centos7防火墙firewalld配置/

mysql忘记密码
  1 关闭MYSQL服务 service mysql stop
  2 打开配置文件 /etc/my.cnf 或者 /etc/mysql/my.cnf
  3 加入如下代码
  [mysqld]
    skip-grant-tables
    
  4   保存 重启服务 service mysql start
