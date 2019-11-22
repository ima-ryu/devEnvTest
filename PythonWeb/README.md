# vagrant + docker + django

自作サンプル

vagrant (centos/7)

docker (postgres/python3)

django

# 最初にdjango雛形作るのにやったこと

```
> cd PythonHello
> vagrant up
> vagrant ssh

> cd project
> docker-compose run web django-admin.py startproject config .
# ここで app/config/settings.py の DATABASE設定を編集する
> docker-compose run web python manage.py startapp helloApp
```


# use

```
> cd PythonWeb
> vagrant up
> curl localhost:8081
```

ブラウザで `http://localhost:8081/admin` で管理画面アクセス。

