FROM daocloud.io/library/mysql:latest
CMD ["bash", "-c", "ALTER USER 'root'@'%' IDENTIFIED BY 'root' PASSWORD EXPIRE NEVER; && ALTER USER 'root'@'%' IDENTIFIED WITH mysql_native_password BY '123456' && grant all privileges on *.* to root@'%' with grant option; && flush privileges;"]
