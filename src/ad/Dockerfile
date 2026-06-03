FROM eclipse-temurin:21-jre

WORKDIR /usr/src/app

COPY build/install/opentelemetry-demo-ad ./build/install/opentelemetry-demo-ad

ENV AD_PORT=9099
EXPOSE ${AD_PORT}

ENTRYPOINT ["./build/install/opentelemetry-demo-ad/bin/Ad"]