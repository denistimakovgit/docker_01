Задание 1

Сборка образа
docker build -t my_nginx:v3 .

Запуск образа:
docker run -d -p 8000:80 my_nginx:v3
