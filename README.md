# Habit Tracker API

Простой API на Django и Django REST Framework для отслеживания привычек.

## Функционал
- Добавление привычек
- Отметка выполнения
- Просмотр списка привычек
- Удаление и редактирование

## Технологии
- Python 3
- Django
- Django REST Framework

## Установка и запуск

```bash
git clone https://github.com/Yamil0702/new-rep.git
cd new-rep
python -m venv venv
venv\Scripts\activate  # или source venv/bin/activate для Linux/macOS
pip install -r requirements.txt  # если создашь этот файл
python manage.py migrate
python manage.py runserver
