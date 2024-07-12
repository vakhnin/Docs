# Docker

[Главная](README.md)

Собрать и запустить все контейнеры<br>
`sudo docker-compose up -d`

Пересобрать и запустить один контейнер<br>
`sudo docker-compose ps --services`<br>
`sudo docker-compose up -d --no-deps --build <название сервиса>`


Все контейнеры (и работающие и остановленные)<br>
`sudo docker ps -a`

Зайти внутрь контейнера<br>
`sudo docker exec -it <ID контейнера> sh`

Очистка всех остановленных контейнеров и образов:<br>
`sudo docker system prune -a`

Остановить все контейнеры<br>
`sudo docker stop $(sudo docker ps -q)`<br>
`sudo docker rmi $(sudo docker images -q)`
