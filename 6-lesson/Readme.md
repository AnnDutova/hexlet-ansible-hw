# Задание 

1. Установка nginx
2. Копирование файла по пути /usr/share/nginx/html/index.html со следующим содержимым:

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hello World!</title>
</head>
<body>
  <h1>Hello World!</h1>
</body>
</html>
```

3. Копирование файла конфигурации по адресу /etc/nginx/nginx.conf:
```
events {

}

http {
  server {
    listen 80 default_server;
  }
}
```
4. Обработчик перезапуска сервиса Nginx, если изменился конфигурационный файл.
Файлы для копирования должны находиться в директории files/

5. Выполните плейбук. Если все выполнилось успешно, по адресу http://SERVER_IP должна быть доступна страница с текстом Hello, World!.

6. Измените конфигурационный файл Nginx, измените listen 80 на listen 8080. Выполните плейбук и откройте страницу по адресу http://SERVER_IP:8080 (с указанием порта)

7. Залейте изменения на Github