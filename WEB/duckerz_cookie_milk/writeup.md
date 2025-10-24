# Печеньки с молочком - Duckerz CTF 
**Категория**: Web  

## Описание
Сайт для ценителей печенек, где нужно работать с куки для получения флага. При входе показывается милый дизайн с печеньками, и куки содержат сессию по умолчанию.

## Решение
1. Открыл сайт и перешёл в DevTools (F12) → "Application" → Cookies.
2. Нашёл куки: `PHPSESSID=e331b8a198ff2e60d4c4143f0f8e01ab` и `username=anonymous`.
3. Подменил значение `username=anonymous` на `username=admin` (правой кнопкой на куки → Edit).
4. Обновил страницу и получил флаг.

## Скриншот
![Куки и флаг](https://github.com/maapik/writeupes_CTF/blob/main/WEB/duckerz_cookie_milk/5.png)
