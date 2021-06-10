ARG BASE_CONTAINER=elyra/kernel-scala:2.4.0
FROM $BASE_CONTAINER

RUN wget https://github.com/SANSA-Stack/SANSA-Stack/releases/download/BACKPORT-0.2.0/sansa-examples-spark_2.11-0.8.0-RC1-backport-jar-with-dependencies.jar && \
    mv sansa-examples-spark_2.11-0.8.0-RC1-backport-jar-with-dependencies.jar /opt/spark/jars/sansa.jar
