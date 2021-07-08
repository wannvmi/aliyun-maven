#

Dockerfile

```Dockerfile
FROM maven:3.8.1-openjdk-11
COPY settings.xml /root/.m2/
```


Build this image:
```bash
docker build -t aliyun-maven:3.8.1-openjdk-11 .
```

