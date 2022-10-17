#利用方法
$ docker-compose down -v
$ docker-compose up -d --build
$ docker-compose exec web python manage.py migrate --noinput
$ docker-compose exec web python manage.py collectstatic --no-input --clear

##ブラウザで確認
http://localhost:1317/
http://localhost:1317/admin

更新テスト