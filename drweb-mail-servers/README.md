#### drweb-mail-servers

Данный репозиторий содержит сценарии docker-compose, которые предназначены для демонстрации возможностей интеграции продуктов Drweb c популярными почтовыми конфигурациями.

Используемые сетевые порты (на системе, где выполняется команда docker-compose):
  
* HTTPS: 4443
  
* SPAMD:  783
* MILTER: 2259
* RSPAMD: 11333

* SMTP:  1025
* SMTPS: 10465
* POP3:  10110
* POP3S: 10995
* IMAP:  10143
* IMAPS: 10993

Настройки сервисов:

* Почтовый домен по-умолчанию: testlab1.test  
* Пользователи (username:password): user1:user1, user2:user2, user3:user3, user4:user4, user5:user5, user6:user6
