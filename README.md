# BUILD

```sh
docker build -t snorql .
```

# RUN 

To run snorql as one-off container do:

```sh
docker run -it --rm -p 8080:80 snorql
```

Open [http://docker.local:8080](http://docker.local:8080) in your browser to use snorql (assuming `docker.local` is an host alias referring to your `YOUR_DOCKER_HOST_IP`).

Exit / kill with `Ctrl+C`
