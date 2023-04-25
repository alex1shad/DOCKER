### создаем контейнер, присваиваем имя 'task1', пробрасываем свой порт 8000 к порту контейнера 80, подменяем файлы html из nginx своим
 docker run --name=task1 -p  8000:80 -d -v /home/alex/WEB_project/DOCKER/Task_1/index:/usr/share/nginx/html nginx
 
 ### Смотрим, что получилось
 curl localhost:8000
