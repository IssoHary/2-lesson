<strong>Урок 2, Git, GitHub, commit</strong>

<strong>Настраиваем Git</strong>
git config --global user.name "Никнейм"
git config --global user.email "email@пример.com"
git config --global --list

<strong>Создаем локальный репозиторий</strong>
Открываем main.py, пишем код, сохраняем.
Процесс создания запускается командой:
git init

<strong>Первый коммит</strong>
Добавляем файл в отслеживание:
git add main.py
Создаем коммит:
git commit -m "first commit"
Проверяем статус репозитория:
git status

README.md - стандартный файл описания проекта
git add . - добавляет все измененные файлы разом
git log - просмотреть историю коммитов
clear - очистить экран терминала

<strong>Подключаемся к GitHub</strong>
git branch -M main
git remote add origin <https://github.com/наш_логин/lesson2-github.git>
git push -u origin main

u origin main — связывает локальную ветку main с удаленной, чтобы в следующий раз можно было писать просто git push