## LoongArch Maven Docker Images

<p align="center"><a href="README.md">English</a> | <a href="README-zh.md">中文</a></p>

Prebuilt Apache Maven Docker images for the LoongArch (loong64) architecture, built on top of [jdk-loong64](https://github.com/kubernetes-loong64/jdk-loong64).

## AnolisOS-based

- [![kubernetesloong64/maven-loong64:3.9.16-8-anolis](https://img.shields.io/docker/v/kubernetesloong64/maven-loong64/3.9.16-8-anolis?arch=loong64&logo=docker&label=kubernetesloong64%2Fmaven-loong64)](https://hub.docker.com/r/kubernetesloong64/maven-loong64/tags)
- [![kubernetesloong64/maven-loong64:3.9.16-11-anolis](https://img.shields.io/docker/v/kubernetesloong64/maven-loong64/3.9.16-11-anolis?arch=loong64&logo=docker&label=kubernetesloong64%2Fmaven-loong64)](https://hub.docker.com/r/kubernetesloong64/maven-loong64/tags)
- [![kubernetesloong64/maven-loong64:3.9.16-17-anolis](https://img.shields.io/docker/v/kubernetesloong64/maven-loong64/3.9.16-17-anolis?arch=loong64&logo=docker&label=kubernetesloong64%2Fmaven-loong64)](https://hub.docker.com/r/kubernetesloong64/maven-loong64/tags)
- [![kubernetesloong64/maven-loong64:3.9.16-21-anolis](https://img.shields.io/docker/v/kubernetesloong64/maven-loong64/3.9.16-21-anolis?arch=loong64&logo=docker&label=kubernetesloong64%2Fmaven-loong64)](https://hub.docker.com/r/kubernetesloong64/maven-loong64/tags)
- [![kubernetesloong64/maven-loong64:3.9.16-25-anolis](https://img.shields.io/docker/v/kubernetesloong64/maven-loong64/3.9.16-25-anolis?arch=loong64&logo=docker&label=kubernetesloong64%2Fmaven-loong64)](https://hub.docker.com/r/kubernetesloong64/maven-loong64/tags)
- [![kubernetesloong64/maven-loong64:3.9.16-26-anolis](https://img.shields.io/docker/v/kubernetesloong64/maven-loong64/3.9.16-26-anolis?arch=loong64&logo=docker&label=kubernetesloong64%2Fmaven-loong64)](https://hub.docker.com/r/kubernetesloong64/maven-loong64/tags)

## Debian-based

- [![kubernetesloong64/maven-loong64:3.9.16-8-debian](https://img.shields.io/docker/v/kubernetesloong64/maven-loong64/3.9.16-8-debian?arch=loong64&logo=docker&label=kubernetesloong64%2Fmaven-loong64)](https://hub.docker.com/r/kubernetesloong64/maven-loong64/tags)
- [![kubernetesloong64/maven-loong64:3.9.16-11-debian](https://img.shields.io/docker/v/kubernetesloong64/maven-loong64/3.9.16-11-debian?arch=loong64&logo=docker&label=kubernetesloong64%2Fmaven-loong64)](https://hub.docker.com/r/kubernetesloong64/maven-loong64/tags)
- [![kubernetesloong64/maven-loong64:3.9.16-17-debian](https://img.shields.io/docker/v/kubernetesloong64/maven-loong64/3.9.16-17-debian?arch=loong64&logo=docker&label=kubernetesloong64%2Fmaven-loong64)](https://hub.docker.com/r/kubernetesloong64/maven-loong64/tags)
- [![kubernetesloong64/maven-loong64:3.9.16-21-debian](https://img.shields.io/docker/v/kubernetesloong64/maven-loong64/3.9.16-21-debian?arch=loong64&logo=docker&label=kubernetesloong64%2Fmaven-loong64)](https://hub.docker.com/r/kubernetesloong64/maven-loong64/tags)
- [![kubernetesloong64/maven-loong64:3.9.16-25-debian](https://img.shields.io/docker/v/kubernetesloong64/maven-loong64/3.9.16-25-debian?arch=loong64&logo=docker&label=kubernetesloong64%2Fmaven-loong64)](https://hub.docker.com/r/kubernetesloong64/maven-loong64/tags)
- [![kubernetesloong64/maven-loong64:3.9.16-26-debian](https://img.shields.io/docker/v/kubernetesloong64/maven-loong64/3.9.16-26-debian?arch=loong64&logo=docker&label=kubernetesloong64%2Fmaven-loong64)](https://hub.docker.com/r/kubernetesloong64/maven-loong64/tags)

### Maven Version

| Maven  |
|--------|
| 3.9.16 |

### Supported JDK Versions

| JDK | Supported |
|-----|-----------|
| 8   | ✅         |
| 11  | ✅         |
| 17  | ✅         |
| 21  | ✅         |
| 25  | ✅         |
| 26  | ✅         |

### Supported Base Images

| OS     | Base Image                  |
|--------|-----------------------------|
| anolis | openanolis/anolisos:23.4    |
| debian | lcr.loongnix.cn/debian:14   |

### Pull Images

Images are published to Docker Hub under [`kubernetesloong64/maven-loong64`](https://hub.docker.com/r/kubernetesloong64/maven-loong64).

```shell
# JDK 8 (anolis)
docker pull kubernetesloong64/maven-loong64:3.9.16-8-anolis

# JDK 8 (debian)
docker pull kubernetesloong64/maven-loong64:3.9.16-8-debian

# JDK 11 (anolis)
docker pull kubernetesloong64/maven-loong64:3.9.16-11-anolis

# JDK 11 (debian)
docker pull kubernetesloong64/maven-loong64:3.9.16-11-debian

# JDK 17 (anolis)
docker pull kubernetesloong64/maven-loong64:3.9.16-17-anolis

# JDK 17 (debian)
docker pull kubernetesloong64/maven-loong64:3.9.16-17-debian

# JDK 21 (anolis)
docker pull kubernetesloong64/maven-loong64:3.9.16-21-anolis

# JDK 21 (debian)
docker pull kubernetesloong64/maven-loong64:3.9.16-21-debian

# JDK 25 (anolis)
docker pull kubernetesloong64/maven-loong64:3.9.16-25-anolis

# JDK 25 (debian)
docker pull kubernetesloong64/maven-loong64:3.9.16-25-debian

# JDK 26 (anolis)
docker pull kubernetesloong64/maven-loong64:3.9.16-26-anolis

# JDK 26 (debian)
docker pull kubernetesloong64/maven-loong64:3.9.16-26-debian
```

### Usage

```shell
# JDK 8
docker run --rm kubernetesloong64/maven-loong64:3.9.16-8-anolis mvn --version
docker run --rm kubernetesloong64/maven-loong64:3.9.16-8-debian mvn --version

# JDK 11
docker run --rm kubernetesloong64/maven-loong64:3.9.16-11-anolis mvn --version
docker run --rm kubernetesloong64/maven-loong64:3.9.16-11-debian mvn --version

# JDK 17
docker run --rm kubernetesloong64/maven-loong64:3.9.16-17-anolis mvn --version
docker run --rm kubernetesloong64/maven-loong64:3.9.16-17-debian mvn --version

# JDK 21
docker run --rm kubernetesloong64/maven-loong64:3.9.16-21-anolis mvn --version
docker run --rm kubernetesloong64/maven-loong64:3.9.16-21-debian mvn --version

# JDK 25
docker run --rm kubernetesloong64/maven-loong64:3.9.16-25-anolis mvn --version
docker run --rm kubernetesloong64/maven-loong64:3.9.16-25-debian mvn --version

# JDK 26
docker run --rm kubernetesloong64/maven-loong64:3.9.16-26-anolis mvn --version
docker run --rm kubernetesloong64/maven-loong64:3.9.16-26-debian mvn --version
```

### Multi-stage Build

This image is designed to be used as a stage in multi-stage Docker builds. Combine it with your build stage to compile Java projects on LoongArch:

```dockerfile
ARG JDK_VERSION=26

FROM kubernetesloong64/maven-loong64:3.9.16-${JDK_VERSION}-debian AS builder
COPY . /build
WORKDIR /build
RUN mvn clean package -DskipTests

FROM kubernetesloong64/jdk-loong64:${JDK_VERSION}-debian
COPY --from=builder /build/target/*.jar /app.jar
ENTRYPOINT ["java", "-jar", "/app.jar"]
```

## License

[Apache License 2.0](LICENSE)
