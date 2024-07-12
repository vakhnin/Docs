# [Docs](README.md) / Docker

Собрать и запустить все контейнеры
```
sudo docker-compose up -d
```

Пересобрать и запустить один контейнер
```
sudo docker-compose ps --services
```
```
sudo docker-compose up -d --no-deps --build <название сервиса>
```


Все контейнеры (и работающие и остановленные)
```
sudo docker ps -a
```

Зайти внутрь контейнера
```
sudo docker exec -it <ID контейнера> sh
```

Очистка всех остановленных контейнеров и образов:
```
sudo docker system prune -a
```

Остановить и удалить все контейнеры
```
sudo docker stop $(sudo docker ps -q)
```
```
sudo docker rmi $(sudo docker images -q)
```

Очистка логов контейнера
```commandline
echo "" > $(docker inspect --format='{{.LogPath}}' <container_name_or_id>)
```
