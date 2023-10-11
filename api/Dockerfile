# Используйте базовый образ с Python
FROM python:3.11

# Установите дополнительные зависимости (если необходимо)
COPY requirements.txt /app/
RUN pip install -r /app/requirements.txt

# Копируйте ваш Python-скрипт в контейнер
COPY api.py /app/

# Укажите рабочую директорию
WORKDIR /app

# Запустите ваш Python-скрипт
CMD ["python", "api.py"]
