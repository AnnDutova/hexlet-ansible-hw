# Задание

Создайте или используйте готовый плейбук, который устанавливает и настраивает Nginx

1. Используя переменные хостов выведите на html-странице имена разных серверов

Пример шаблона:
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
  <h2>This is server {{ server_name }}!</h2>
</body>
</html>
```

2. Выполните плейбук. Если все выполнено успешно, то зайдя по адресу на каждый из серверов, вы увидите разные отображаемые имена

3. Залейте изменения на Github