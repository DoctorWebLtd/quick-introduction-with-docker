#### Quick introduction with Docker (Beta)

Данный репозиторий предназначен для быстрого развертывания продуктов Drweb. Сделано это для того, чтобы пользователи могли быстро оценить возможности продуктов в связке с популярным серверным ПО.
     
     
**Требования:**

1. Действительный или пробный ключ для [продуктов Drweb](https://products.drweb.ru/linux) (можно использовать BETA* ключ)
2. Операционная система Linux
3. [Docker Engine](https://www.docker.com)
4. [Docker Compose](https://docs.docker.com/compose/)


**Быстрый старт:**

1. git clone https://github.com/DoctorWebLtd/quick-introduction-with-docker.git
2. Выбрать доступную конфигурацию для нужного продукта
4. Изменить путь до ключа в файле docker-compose.yaml
3. Выполнить docker-compose pull && docker-compose up --force-recreate

**BETA ключ выдается во время выпуска продуктов, которые имеют статус BETA, он ограничен по времени и продуктам, может быть заменен в любой момент.*
