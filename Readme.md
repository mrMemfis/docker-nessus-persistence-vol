# How to use Nessus scanner in docker with persistence volume

1. Create persistance volume (will be created in **/var/lib/docker/volumes**):

```
docker volume create --name=nessuspersistence
```

2. Fill the **.env** file with your variable values

3. Run docker-compose
```
docker-compose up -d
```
