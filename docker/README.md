# Docker - bidipeppercrap.com
Before you build the image, you have to set the permission for everyone on `web` and `web-console` directory:

```chmod a+rwx web web-console```

Once you have that done, you can build and run the image with:

```
$ docker-compose build
$ docker-compose run -d
```

## Manager
In order to use the manager, you have to build and run the image with `docker-compose`:

```
$ docker-compose -f manager.yml build
$ docker-compose -f manager.yml run manager /bin/sh
```