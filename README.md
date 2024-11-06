# NekoCraft 🎌🐾

This project is a [Django](https://www.djangoproject.com/) backend for the NekoCraft website.

NekoCraft is a Minecraft server that allows players to enjoy an anime-themed world with friends.

Этот проект представляет собой бэкенд на [Django](https://www.djangoproject.com/) для сайта NekoCraft.

NekoCraft — это Minecraft сервер, который дает возможность играть с друзьями в мире, выполненном в стиле аниме.


## 🌸 Installation / Установка

Clone the repository.
Use the following command to clone the repository:

Клонируйте репозиторий.
Для клонирования репозитория используйте следующую команду:

```bash
git clone https://github.com/davlat-gbpp/NekoCraft.git
```

Navigate to the project directory

Перейдите в директорию проекта

```bash
cd NekoCraft
```

Create a virtual environment

Создайте виртуальное окружение

```bash
python -m venv venv
```

Activate the virtual environment

Активируйте виртуальное окружение

On Windows:

```bash
venv\Scripts\activate
```

On macOS/Linux:

```bash
source venv/bin/activate
```

Install the required dependencies

Установите необходимые пакеты

```bash
pip install -r requirements.txt
```

Apply migrations

Примените миграции

```bash
python manage.py migrate
```

Run the development server

Запустите сервер разработки

```bash
python manage.py runserver
```

Now, the project should be running on your local server.

Теперь проект должен быть установлен и запущен на локальном сервере.


## 🎎 Technologies / Технологии
  - Django 5.1.2
  - Pillow 11.0.0
  - Django REST Framework 3.15.2

## 🏯 Databases / Базы данных
  - SQLite
  - PostgreSQL (used in production)

Note: This project uses SQLite for development and testing. However, in a production environment, we recommend using PostgreSQL for better performance and scalability.

Примечание: Этот проект использует SQLite для разработки и тестирования. Однако в реальной среде мы рекомендуем использовать PostgreSQL для улучшения производительности и масштабируемости.

