# UrbanProject-Django

Проект в рамках обучения в Urban University.  
Используемая версия Python 3.12

## Установка

Следуйте этим инструкциям для установки проекта на локальную машину для разработки и тестирования.
1. Клонируйте репозиторий:
    ```bash
    git clone https://github.com/ZehrBit/UrbanProject-Django.git
    cd UrbanProject-Django
    ```
2. Создайте и активируйте виртуальное окружение:
    ```bash
    python -m venv venv
    source venv/bin/activate  # Для Windows используйте `venv\Scripts\activate`
    ```
3. Установите зависимости:
    ```bash
    pip install -r requirements.txt
    ```
4. Создайте базу данных и выполните миграции:
    ```bash
    python manage.py migrate
    ```
5. Создайте суперпользователя:
    ```bash
    python manage.py createsuperuser
    ```

## Запуск на локальном компьютере
1. Запустите сервер разработки:
```bash
python manage.py runserver
```

2. Перейдите по адресу в вашем браузере, чтобы увидеть работающий проект.
```bash
http://127.0.0.1:8000/
```

## Контакты
Email: zehrbit@gmail.com  
Telegram: https://t.me/zehrbit
