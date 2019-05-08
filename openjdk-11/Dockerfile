FROM registry.access.redhat.com/ubi8/ubi-minimal

ENV JAVA_MAJOR_VERSION=11 \
    JAVA_HOME=/usr/lib/jvm/jre-11

RUN microdnf install java-11-openjdk-headless \
  && microdnf clean all
