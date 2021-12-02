Polecenie do uruchomienia:

``` docker compose up -d ```

Aby utworzyc testowa baze danych: 

```  docker exec project-mysql-1 mysql --execute="CREATE DATABASE baza" --user=root --password=root ``` 

Struktura projektu:

``` docker container run --rm -it --name mgraph -v $(pwd):/input pmsipilot/docker-compose-viz render -m image docker-compose.yml ``` 

![docker-compose](https://user-images.githubusercontent.com/84234350/144516870-186cb5de-16e9-41f9-a462-8d6eb10db611.png)
