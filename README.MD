DjangoCountries

Инструкция по развертыванию проекта

1.python3 -m venv django_venv - создание venv

2.django_venv/Script/activate

3.pip install -r requirements.txt

4.python manage.py migrate

5.python manage.py loaddata countries.json

6.python manage.py runserver

Запуск терминала в контексте django:
python manage.py shell_plus --ipython