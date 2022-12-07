# Обрезка ссылок с помощью bitly
На вход программа получает ссылку, в ответ создает и возвращает битлинк, который
считает количесво кликов. Если на вход программе поступает ранее созданный
битлинк, то возвращает количество кликов.
### Как установить
Должен быть установлен python3.
Затем используйте `pip`(или `pip3`, если есть конфликт с Python2) для установки
зависимостей:
 ```bash
 pip install -r requirements.txt
 ```
 ### Как настроить ключи доступа bitly
 * Для изоляции проекта рекомендуется использовать 
 [virtualenv/venv](https://docs.python.org/3/library/venv.html).
 *  Чтобы получить ключ, нужно зарегистрироваться на [bitly](https://bitly.com/). 
 В личном кабинете сгенерировать Access Token и положить в .env файл:
 ```text
 TOKEN='ВашКлюч'
 ```

 ### Цель проекта

Код написан в образовательных целях 
на онлайн-курсе для веб-разработчиков [dvmn.org](dvmn.org).
