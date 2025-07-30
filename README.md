# ELK-netology-hw
## Домашнее задание к занятию «ELK»
Задание 1. Elasticsearch
Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.

Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.

## Решение 1.
<img width="732" height="297" alt="Снимок273" src="https://github.com/user-attachments/assets/2be682a8-338f-4e49-b48b-48163f6ef663" />

## Задание 2. Kibana
Установите и запустите Kibana.

Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.

## Решение 2.
<img width="1852" height="990" alt="Снимок276" src="https://github.com/user-attachments/assets/d0fc7138-76b3-419a-b675-dbe9ba0d09e2" />

## Задание 3. Logstash
Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.

## Решение 3.
<img width="1833" height="902" alt="Снимок277" src="https://github.com/user-attachments/assets/8108fcec-52bf-4aa2-aa11-34af223f7e63" />

## Задание 4. Filebeat.
Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.

## Решение 4.
<img width="1838" height="976" alt="Снимок281" src="https://github.com/user-attachments/assets/67800777-bf07-47db-83c9-566248ececae" />

