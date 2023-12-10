# PyQt5. <br/>Тестовое задание.


![alt-текст](https://github.com/HeyArtem/HeyArtem/PyQt_final/additional_materials/pyqt5.png "logo")


## Описание:
Это тестовое задание (оригинал задания в папке additional_materials), выполненое с помощью библиотеки PyQt.
<br/>Скрипт:
<br/>- загружает pdf фаил
<br/>- дает возможность навигации по страницам
<br/>- выделяет необходимую область, при помощи мышки
<br/><br/>
<hr>


## Тех.детали:
* fitz
* PyQt5
* sys
<br/><br/>
<hr>


## Особенности:
Если при работе с fitz выходит ошибка:
ModuleNotFoundError: No module named 'frontend'
Лекарство:
$ pip install PyMuPDF
<br/><br/>
<hr>


## Что бы установить и запустить проект:
- создать директорию на компьютере
- открыть нужный репозиторий-Code-HTTPS-скопировать ссылку
- $ git clone + ссылка
- перейти в паку с проектом
- $ python3 -m venv venv -создать виртуальное окружение
- $ source venv/bin/activate -активировать виртуальное окружение
- $ pip install -U pip setuptools
- $ pip install -r requirements.txt -установить библиотеки из requirements.txt
- $ code . -открыть проект в VS Code (или другом редакторе кода)
- запустить main.py
