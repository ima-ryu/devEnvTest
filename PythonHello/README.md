# vagrant + docker + python

自作サンプル

vagrant (image: centos/7)
docker (image: python3)

# use

```
> cd PythonHello
> vagrant up
> vagrant ssh

(into vm)

> cd app/dockers
> docker exec -it python /bin/bash

(into docker container)

> python hello.py
```

