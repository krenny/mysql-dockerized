# mysql-dockerized

Please dont even ask why I made this....
However this repo provides mysql and phpmyadmin dockerized.


make changes like mysql-root pw or ports
```
nano docker-compose.yml
```

if you would like to modify your mysql config
```
nano mysql/my.cnf
```


to start the container
```
docker-compose up -d
```

databases will be stored at
>mysql/data/
