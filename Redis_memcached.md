# Домашнее задание к занятию «Кеширование Redis/memcached»

## Выполнил Савийкий Андрей

### Задание 1. Кеширование 

Приведите примеры проблем, которые может решить кеширование. 

#### Ответ:

- Кэш, может решить роблему скорости ответа, ускорив её;
- Проблему резкого роста трафика (внезапный наплыв пользователей), за счет сглаживания бустов трафика;
- Проблему с производительностью, за счет отправки в кэш данных, к которым чаще всего происходит обращение;
- И кэш помагает с экономией ресурсов базы данных, применяя кэширование тяжелых запросов.

---

### Задание 2. Memcached

Установите и запустите memcached.

#### Результат:

![1memcached](https://github.com/FoxySOTKA/SYSDB-20/assets/141597247/537f0839-8946-4428-8d91-375ed3d69b26)

##### Выполнение команды systemctl status memcached.

---

### Задание 3. Удаление по TTL в Memcached

Запишите в memcached несколько ключей с любыми именами и значениями, для которых выставлен TTL 5. 

#### Результат:

![5key_memcached](https://github.com/FoxySOTKA/SYSDB-20/assets/141597247/0a5c35db-0f9e-4a7b-8321-eef6b90b2990)

##### Демонстрация удаления ключей из базы спустя 5 секунд.

---

### Задание 4. Запись данных в Redis

Запишите в Redis несколько ключей с любыми именами и значениями. 

#### Результат:

![redis-cli](https://github.com/FoxySOTKA/SYSDB-20/assets/141597247/e7da963e-8636-4f90-a603-ca61b2196c9d)


##### Через redis-cli достаю все записанные ключи и значения из базы.
