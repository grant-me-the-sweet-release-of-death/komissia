1) Клонирование репозитория:

git clone https://github.com/grant-me-the-sweet-release-of-death/komissia
cd practice

2) Создайте виртуальное окружение и активируйте его:
python -m venv venv
source venv/bin/activate

3) Установите зависимости:
pip install -r requirements.txt

4) Cоздание и миграция базы данных:
flask db init
flask db migrate
flask db upgrade

5) Произведите настройку переменных окружений в .env файле

6) Запустите приложение:
python app.py

Доступ: http://127.0.0.1:5000/
