### docker-nginx-proxy-1

```
[yuzunoha@localhost docker-nginx-proxy-1]$ cat /etc/os-release
NAME=Fedora
VERSION="31 (Server Edition)"
```

```
[yuzunoha@localhost docker-nginx-proxy-1]$ docker --version
Docker version 19.03.6, build 369ce74a3c
```

```
[yuzunoha@localhost docker-nginx-proxy-1]$ docker-compose --version
docker-compose version 1.25.5, build 8a1c60f6
```

```
[yuzunoha@localhost docker-nginx-proxy-1]$ dnf list | grep docker-ce
containerd.io.x86_64 1.4.3-3.1.fc31 @docker-ce-stable
docker-ce.x86_64 3:19.03.6-3.fc31 @docker-ce-stable
docker-ce-cli.x86_64 1:19.03.6-3.fc31 @docker-ce-stable
docker-ce.x86_64 3:20.10.3-3.fc31 docker-ce-stable
docker-ce-cli.x86_64 1:20.10.3-3.fc31 docker-ce-stable
docker-ce-rootless-extras.x86_64 20.10.3-3.fc31 docker-ce-stable
```
