# Скачивание контейнера
docker pull eliotald/planitpoker 
# Запуск сборки
docker build -t planitpoker .
# Запуск контейнера
docker run -p 8080:8080 planitpoker