#### Quick introduction to Install Beta version Drweb Mail Servers For Unix with Docker

Данный репозиторий предназначен для быстрого развертывания продукта Dr.Web для почтовых серверов Unix. С помощью этого репозитория пользователи могут быстро оценить возможности продуктов Dr.Web в связке с популярными почтовыми серверами.
    
    
**Требования:**

1. Действительный ключевой файл для Drweb для почтовых серверов для Unix (https://products.drweb.ru/linux) , либо ключ для Beta* тестирования Drweb для почтовых серверов для Unix
2. Операционная система Linux
3. [Docker Engine](https://www.docker.com)
4. [Docker Compose](https://docs.docker.com/compose/)


**Быстрый старт:**

1. Выполните команду git clone https://github.com/DoctorWebLtd/quick-introduction-with-docker.git.
2. Выберите доступную конфигурацию для нужного продукта.
4. Измените путь до ключевого файла в файле docker-compose.yaml.
3. Выполните команду docker-compose pull && docker-compose up --force-recreate.

**Ключевой файл программы бета-тестирования выдается для продуктов, которые имеют статус бета. Данный ключевой файл имеет ограничение по времени и по продуктам, для которых он может использоваться. Этот ключевой файл может быть заменен в любой момент.
