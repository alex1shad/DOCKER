### Сборка образа
docker build ./ --tag task2

### Запуск контейнера
docker run --name task2_run -d -p 8000:8000 task2:latest