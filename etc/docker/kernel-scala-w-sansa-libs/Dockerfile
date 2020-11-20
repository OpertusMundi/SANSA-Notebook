ARG BASE_CONTAINER=elyra/kernel-scala:2.3.0
FROM $BASE_CONTAINER

RUN wget https://github.com/SANSA-Stack/SANSA-Stack/releases/download/BACKPORT-0.1.0/sansa-ml-spark_2.11-BACKPORT-0.1.0-jar-with-dependencies.jar && \
    mv sansa-ml-spark_2.11-BACKPORT-0.1.0-jar-with-dependencies.jar /opt/spark/jars/sansa.jar

