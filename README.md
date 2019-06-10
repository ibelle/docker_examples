# Build and Run directly

```bash
$ cd <EXAMPLE DIR>/web
$ docker build -t docker_hello[XXX] .
$ docker run [-d] -p 5000:5000 docker_hello[XXX]
```

### Note: If multiple containers are running find additonal port mappings like 8080:5000

# Run Via docker-compose

```bash
$ cd<EXAMPLE DIR> (with a docker-compose.yml file)
$ docker-compose up [-d]
```
