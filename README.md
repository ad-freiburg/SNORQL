# BUILD

```
docker build -t snorql .
```

# RUN 

run as one-off container

```
docker run -it --rm -p 8080:80 snorql
```

in your browser goto http://<dockerip>:8080 to use snorql

Exit / kill with `Ctrl+C`
