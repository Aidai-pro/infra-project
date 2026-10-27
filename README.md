Midterm devOPs Kazakova Aidai
Отредактировано в гитхаб
## Запуск в Docker


```bash
docker build -t infra-web:1.0 docker/
docker run -d --name infra-web -p 8080:80 infra-web:1.0
curl http://localhost:8080
```
