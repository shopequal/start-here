FROM registry.redhat.io/openjdk/openjdk-8-rhel8
USER root

MAINTAINER Tosin Akinsoho  <tosin@redhat.com>

RUN set -x \
    && mkdir -p /swagger-api/out \
    && dnf install wget -y \
    && wget -qO- https://api.github.com/repos/swagger-api/swagger-codegen/tarball/master | tar zxv -C swagger-api \
    && mv /swagger-api/swagger-api-swagger-codegen* /swagger-api/swagger-codegen/ \
    && ln -s /swagger-api/swagger-codegen/modules/swagger-codegen/src/test/resources/2_0/ /swagger-api/yaml


VOLUME /swagger-api/out

WORKDIR /swagger-api/out

COPY docker-entrypoint.sh /

RUN cd /swagger-api/swagger-codegen && \
    mvn -am -pl "modules/swagger-codegen-cli" package -DskipTests && \
    rm -rf ${MAVEN_HOME}/.m2/repository

ENTRYPOINT ["/docker-entrypoint.sh"]

CMD ["help"]
