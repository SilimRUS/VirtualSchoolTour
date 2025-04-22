# Flask App for Render.com

## Запуск локально

1. Установите зависимости:
   ```
   pip install -r requirements.txt
   ```
2. Запустите приложение:
   ```
   python app.py
   ```

## Деплой на Render.com

1. Загрузите этот репозиторий на GitHub.
2. Создайте новый Web Service на https://render.com/ и подключите репозиторий.
3. В поле Start Command укажите:
   ```
   gunicorn app:app
   ```
4. Дождитесь деплоя и получите ссылку на сайт.
