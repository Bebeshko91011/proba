Клонировать репозиторий
git clone https://github.com/DJWOMS/cook_blog.git
3) Создать виртуальное окружение
cd cook_blog

python -m venv venv
4) Активировать виртуальное окружение
Linux

source venv/bin/activate
Windows

./venv/Scripts/activate
5) Устанавливить зависимости:
pip install -r req.txt
6) Выполнить команду для выполнения миграций
python manage.py migrate
8) Создать суперпользователя
python manage.py createsuperuser
9) Запустить сервер
python manage.py runserver