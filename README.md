# Обрезка ссылок с помощью Битли

Скрипт предназначен для сокращения ссылок, а также подсчёта количества переходов по битлинку с помощью API сервиса Bitly.

### Как установить


Для использования скрипта необходимо зарегистрироваться в сервисе [bitly.com](https://bitly.com/) и получить токен (GENERIC ACCESS TOKEN). Токен выглядит так: `17c09e20ad155405123ac1977542fecf00231da7`. Ссылка на получание токена есть в [документации](https://dev.bitly.com).

Токен нужно присвоить переменной BITLY_TOKEN в файле .env:

```
BITLY_TOKEN = "ВашТокен"
```

Python3 должен быть уже установлен. 
Затем используйте `pip` (или `pip3`, есть конфликт с Python2) для установки зависимостей:
```
pip install -r requirements.txt
```

### Цель проекта

Код написан в образовательных целях на онлайн-курсе для веб-разработчиков [dvmn.org](https://dvmn.org/).

