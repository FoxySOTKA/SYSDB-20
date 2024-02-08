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


##### Запрос GET /_cluster/health?pretty на странице http://<ip вашего сервера>:5601/app/dev_tools#/console интерфейса Kibana.

---

### Задание 3. Logstash

Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch. 

#### Результат:


##### Логи Nginx в интерфейсе Kibana.

---

### Задание 4. Filebeat. 

Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat. 

#### Результат:


##### Логи Nginx в интерфейсе Kibana, которые были отправлены через Filebeat.
