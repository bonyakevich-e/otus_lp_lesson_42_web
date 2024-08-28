### OTUS Linux Professional Lesson #42 | Subject: Web протоколы, Nginx, Динамический веб

#### Цель: 
- Получить практические навыки в настройке инфраструктуры с помощью манифестов и конфигураций;
- Отточить навыки использования ansible/vagrant/docker.

#### Описание домашнего задания
Варианты стенда:
- nginx + php-fpm (laravel/wordpress) + python (flask/django) + js(react/angular);
- nginx + java (tomcat/jetty/netty) + go + ruby;
- свои комбинации

Реализации на выбор:
- на хостовой системе через конфиги в /etc;
- деплой через docker-compose.

#### Процедура выполнения домашнего задания

Будем использовать вариант стенда __"nginx + php-fpm (wordpress) + python (django) + js(node.js)"__

Для развёртки wordpress используем СУБД MySQL. 


Дополнительные команды, которые использовались при выполнении домашнего задания:
`docker ps` - список запущенных контейнеров
`docker rm --force <id>` - удалить запущенный контейнер  
`docker-compose up -d <service>` - запустить только указанный сервис из docker-compose.yml
`docker-compose logs` - посмотреть логи сервисов
