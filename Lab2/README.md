# Как запустить лабораторную

Для запуска нужен Python 3.13. Сначала кладём данные из задания в папку `data` внутри проекта.

Потом открываем PowerShell в папке проекта, создаём виртуальное окружение и ставим библиотеки.

```powershell
python -m venv .venv
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
.\.venv\Scripts\python.exe -m notebook
```

В Jupyter открываем ноутбук лабораторной и выбираем `Restart Kernel and Run All Cells`. Первый запуск может занять несколько минут, так как модели обучаются на CPU.
