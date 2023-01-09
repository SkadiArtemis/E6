Итоговое задание по модулю Е6
Проект состоит из клиента на JavaScript и бэкенда на Django Rest Framework.

Реализован базовый мессенжер со следующими функциями:

Отправка и получение сообщений;
Создание, редактирование и удаление групповых чатов и переписка в них (управление чатами по REST API,
а переписка так же, как в обычных чатах, но с использованием на сервере идеологии «комнат»);
Редактирование личной информации пользователя (имя и аватар);
Просмотр списка других пользователей с переходом на отправку им сообщений.
Все библиотеки, необходимые для работы проекта указаны в файле requirements.txt

Автор проекта: skadi_artemis

Группа SkillFactory: FPW-76

Для запуска сервера необходим IDE (я использую PyCharm или VSCODE), в котором установить фреймворк Django
и следующие библиотеки:

pip install django

pip install djangorestframework

pip install django-cors-headers

pip install easy-thumbnails pip install channels


Команда запуска сервера стандартная: py manage.py runserver


Для запуска клиента нужно скопировать на комьютер файлы из папки "Клиент на JS"
и запустить в браузере index.html
Клиент проверяла в браузере Chrome 
