# IPlogger

## В разработке применяется ##

* [Python 3.9](https://www.python.org/) - язык программирования

* [FastAPI](https://fastapi.tiangolo.com) - основной фреймворк

* [sqlalchemy](https://www.sqlalchemy.org/) - The Python SQL Toolkit and Object Relational Mapper

## Описание репозитория ##

* /mod
  * /maxmind - папка с базами данных IP адресов
  * /models - папка с модулями моделей и функций БД
  * api.py - модуль отвечает за описание API, а так же валидацию данных.
  * db.py - модуль отвечает за работу БД
  * geo.py - модуль работы с базами данных IP адресов
  * utils.py - утилиты
* /templates - шаблоны для вывода статистики сервера в браузере.
  * base.html - базовый шаблон с основными элементами меню, он имплементируется в каждый рабочий шаблон.
  * index.html - рабочий шаблон главной страницы.
  * status.thml - рабочий шаблон страницы со статусом работы сервера.
* create_db.py - файл для создание БД
* main.py - основной код сервера

## Установка ##

### Windows:

```bash
git clone https://github.com/vsecoder/iplogger
cd iplogger
pip install -r requirements.txt
python main.py
```

### Linux:

```bash
git clone https://github.com/vsecoder/iplogger
cd iplogger
pip3 install -r requirements.txt
python3 main.py
```
