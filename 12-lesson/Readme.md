# Задание

1. Воспользуемся простым фильтром, который приводит строку к верхнему регистру

1) Создайте новую переменную, которая содержит строку This is server web1!, где web1 это динамическое имя сервиса (взятое из фактов)
2) В шаблоне HTML файла templates/index.html.j2 Выведите сообщение в верхнем регистре с помощью фильтра upper.

2. Также выведем текущую дату. Используйте факты, и выведите текущую дату в любом формате.

3. Залейте изменения на Github

В результате получится следующее:
```
<html lang="en"><head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hello World!</title>
</head>
<body>
  <h1>Hello World!</h1>
  <h2>THIS IS SERVER WEB1!</h2> <!-- Эта строка была приведена в верхний регистр с помощью фильтра -->
  <small>Deployed at: Вт 21 дек 2021 20:18:03</small> <!-- Локализованная дата -->
</body>
</html>
```