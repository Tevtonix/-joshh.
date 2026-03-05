# -joshh.

# Установка зависимостей
pip install -r requirements.txt

# Запуск всех тестов
pytest -v

# Запуск с отчетом о покрытии
pytest -v --cov=schemas --cov-report=html

# Запуск конкретного теста
pytest test_users.py::test_user_schema_validation -v
