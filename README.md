# delcibo_media_server

Создать имя пользователя</br>
```
  mysql
  CREATE USER 'delcibo'@'delcibodatabaseserv.ddns.net' IDENTIFIED BY '9174253qQ';
  GRANT ALL PRIVILEGES ON *.* TO 'delcibo'@'delcibodatabaseserv.ddns.net' WITH GRANT OPTION;
  #редактируем файл 
  sudo nano /etc/mysql/mysql.conf.d/mysqld.cnf
  bind-address=0.0.0.0
  sudo service mysql restart

  
```

