# Задание 

Зарегистрируем результат выполнения команды в переменную, а саму переменную выведем на HTML странице.

1. Добавьте команду установки пакета cowsay
2. Зайдите по ssh на один из серверов. Запустите команду cowsay с сообщением:
```
cowsay "This is server server_name!"
_________________________
< This is server server_name! >
-------------------------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||
```

3. Добавьте в начало плейбука с установкой Nginx

4. Зарегистриуйте результат выполнения команды cowsay в переменную cowsay_result.

5. Модифицируйте шаблон templates/index.html.j2 и добавьте вывод команды cowsay на страницу. Чтобы результат на странице был сформатирован, оберните его в теги <pre><code>

6. Залейте изменения на Github

В результате получится следующая страница:
```
<html lang="en"><head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hello World!</title>
</head>
<body>
  <h1>Hello World!</h1>
  <h2>THIS IS SERVER UBUNTU-S-1VCPU-1GB-FRA1-02!</h2>
  <pre><code> _____________________________
/ This is server              \
\ ubuntu-s-1vcpu-1gb-fra1-02! /
 -----------------------------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||</code></pre>
  <small>Deployed at: Пт 24 дек 2021 15:26:10</small>


</body></html>
```