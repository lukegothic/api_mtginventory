release: flask db upgrade
web: gunicorn api_mtginventory.app:create_app\(\) -b 0.0.0.0:$PORT -w 3
