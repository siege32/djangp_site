Инструкция по запуску проекта
Описание проекта
Данный проект представляет собой веб-приложение на Django, которое предоставляет функциональность для работы с движением денежных средств, позволяя пользователю добавлять, редактировать. Фильтрация отсутствует из-за недостатка времени для сдачи проекта. Проект содержит в себе: 
my_site - текущая конфигурация проекта;
main_page - основное приложение;
db.sqlite3 - БД приложения;
manage.py - сервер разработки.

Шаги для запуска
1. Для начала клонируйте репозиторий проекта:
git clone https://github.com/siege32/django_site.git
2. После клонирования репозитория перейдите в папку с проектом
3. Войдите в виртуальное окружение с помощью команды ".\venv\Scripts\activate"
4. Перейдите в папку dj\main
5. Запустить сервер разработки: 
python manage.py runserver
6. Открыть приложение в браузере. 
Перейдите по следующему адресу в вашем браузере:
http://127.0.0.1:8000/
7. Остановка сервера. 
Для остановки сервера нажмите Ctrl+C в терминале, где он был запущен.
8. Деактивация виртуальной среды производистя засчет команды deactivate.

Заключение
Теперь вы можете использовать веб-приложение для управления записями о движении денежных средств.
