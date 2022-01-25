# 製作docker image
```bash
sudo docker build -t alpine-python --no-cache --build-arg ENV_NAME=test .
```

# 啟動docker-compose
```bash
sudo docker-compose up -d
```