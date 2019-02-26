FROM registry.cn-shenzhen.aliyuncs.com/songhuan/hub:java8

COPY target/spring-boot-cxf-service-0.0.1-SNAPSHOT.jar /app.jar
ADD run-java.sh /
RUN chmod +x /run-java.sh
WORKDIR /opt/code
EXPOSE 8080
CMD /run-java.sh