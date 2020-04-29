## Jupyter Lab sample

### build
```
docker build .
```

### run
```
docker run -p 8888:8888 -v $HOME/Jupyter-Lab-docker:/work --name my-lab 6124d9f58b8e
```
http://localhost:8888/ にアクセス

### docker command
コンテナ一覧
```
docker ps -a
```

## 参考
* https://datawokagaku.com/startjupyternote/
