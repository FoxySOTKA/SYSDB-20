# Домашнее задание к занятию «ELK»

## Выполнил Савицкий Андрей

### Задание 1. Elasticsearch 

Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный. 

####  Результат:

<img width="446" alt="curl-XGET" src="https://github.com/FoxySOTKA/SYSDB-20/assets/141597247/ae7896d5-bfd2-45ab-9462-0932405e2a3c">

##### Демонстрация команды 'curl -X GET 'localhost:9200/_cluster/health?pretty'

---

### Задание 2. Kibana

Установите и запустите Kibana.

#### Результат:

<img width="876" alt="get" src="https://github.com/FoxySOTKA/SYSDB-20/assets/141597247/db902d62-915c-45e0-8b3d-44a1fd1d0cd9">

##### Запрос GET /_cluster/health?pretty на странице моего сервера в интерфейсе Kibana.

---

### Задание 3. Logstash

Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch. 

#### Результат:

<img width="761" alt="logyNginx" src="https://github.com/FoxySOTKA/SYSDB-20/assets/141597247/db6aacf9-99fe-4447-aa3d-8f3d235a9319">

##### Логи Nginx в интерфейсе Kibana.

---

### Задание 4. Filebeat. 

Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat. 

#### Результат:


##### Логи Nginx в интерфейсе Kibana, которые были отправлены через Filebeat.
