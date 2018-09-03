#基础镜像
FROM java:8-jre

#作者
MAINTAINER Reshine Zhao <zhihong.zhao@qq.com>

ADD ./target/registry-1.0-SNAPSHOT.jar /app/registry.jar
CMD ["java", "-Xmx200m", "-jar", "/app/registry.jar"]

EXPOSE 8761