# Try Visual Studio Code Server in container

```console
docker build -t vscodeserver Docker/
docker run -v $(pwd):/workspace:cached -p 127.0.0.1:8000:8000 -t vscodeserver
```
