# Пример приложения с GUI на базе PyQt

Системные требования: создать виртуальное окружение на базе Python 3.5 - 3.9.

1. Установить пакеты:

`pip install -r requirements.txt`

2. Отредактировать файлы *.ui можно с помощью:

`venv\lib\site-packages\qt5_applications\qt\bin\designer.exe`

3. Откомпилировать *.ui в *.py можно с помощью:

`venv\scripts\pyuic5.exe main.ui -o main_ui.py`
