release: python manage.py migrate
web: daphne apexindustries.asgi:application --port $PORT --bind 0.0.0.0 -v2
chatworker: python manage.py runworker --settings=apexindustries.settings -v2