## СТАТИСТИКА ВАКАНСИЙ ПРОГРАММИСТОВ В ГОРОДЕ МОСКВА
<hr>

Данный скрип получает статистические данные о количестве вакансий программистов и средней заработной платы с двух сайтов:
* [www.headhunter.ru](http://www.headhunter.ru)
* [www.superjob.ru](http://www.superjob.ru)

Данные выводятся в разрезе 7 языков программирования: 'Python', 'Java', 'JavaScript', 'Go', 'PHP', 'C++', '1C'.

Запускают скрипт без параметров

```
    >> python.exe main.py
```	
В данной разработке инициализируются следующие переменные окружения:
- `SUPERJOB_SECRETKEY` - переменная в которой хранится секретный ключ, необходимый для подключения к api сайта [www.superjob.ru](http://www.superjob.ru)
		
Данные переменные инициализируются значениями заданными в .env файле.

Информацию о ходе выполнения скрипт пишет в файл log.txt, который должен находится в корневой папке скрипта.

#### КАК УСТАНОВИТЬ
<hr>

Для установки необходимо отредактировать файл .env, в котором заполнить SECRETKEY.

Python3 должен быть уже установлен. Затем используйте pip (или pip3, есть есть конфликт с Python2) для установки зависимостей:

```
    >> pip install -r requirements.txt
```

### ЦЕЛЬ ПРОЕКТА
<hr>

Код написан в образовательных целях, для изучения возможностей api, на онлайн-курсе для веб-разработчиков [dvmn.org](https://dvmn.org).
