# Kafka y Spark Streaming

## Descripcion
Proyecto de procesamiento de datos simulados de sensores usando Apache Kafka y Apache Spark Structured Streaming.

## Datos
El productor genera datos de sensores con identificador, temperatura, humedad y marca de tiempo.

## Archivos
- kafka_producer.py: genera y envia datos al topico sensor_data de Kafka.
- spark_streaming_consumer.py: consume los datos y calcula promedios de temperatura y humedad por sensor en ventanas de un minuto.

## Requisitos
- Python 3
- Apache Kafka
- Apache Spark con soporte para Kafka
- Biblioteca kafka-python

## Estado
Pendiente de comprobar la ejecucion integrada de Kafka y Spark Streaming.
