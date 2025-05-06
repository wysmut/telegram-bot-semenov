# telegram-bot-semenov

      django/
      ├── docker/
      │   ├── Dockerfile
      │   ├── docker-compose.yml
      ├── manage.py
      ├── django/
      │   ├── __init__.py
      │   ├── settings.py
      │   ├── urls.py
      │   ├── wsgi.py
      │   ├── asgi.py
      │   └── secret.py
      ├── core/
      │   ├── __init__.py
      │   ├── admin.py
      │   ├── apps.py
      │   ├── models.py
      │   ├── views/
      │   │   ├── __init__.py
      │   │   ├── bot_views.py
      │   │   ├── order_views.py
      │   │   ├── report_views.py
      │   │   ├── user_profile_views.py
      │   │   └── api_views.py
      │   ├── urls/
      │   │   ├── __init__.py
      │   │   ├── bot_urls.py
      │   │   ├── order_urls.py
      │   │   ├── report_urls.py
      │   │   ├── user_profile_urls.py
      │   │   └── api_urls.py
      │   ├── migrations/
      │   │   └── __init__.py
      │   └── api/
      │       ├── __init__.py
      │       ├── serializers.py
      │       ├── views.py
      │       └── urls.py
      ├── bot/
      │   ├── __init__.py
      │   ├── bot.py
      │   └── handlers/
      │       ├── __init__.py
      │       ├── orders_handler.py
      │       ├── inline_keyboard.py
      │       └── calendar_handler.py
      ├── tests/
      │   ├── __init__.py
      │   ├── test_bot.py
      │   ├── test_orders.py
      │   ├── test_reports.py
      │   ├── test_user_profiles.py
      │   └── test_api.py
      ├── .env
      └── requirements.txt
