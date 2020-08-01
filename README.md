# Case NYC Taxi Trips

## Bibliotecas Importantes
- <a href="https://spark.apache.org/docs/2.4.5/">Spark</a>
- <a href="https://kafka.apache.org/22/documentation.html">Kafka</a>
- <a href="https://flume.apache.org/FlumeUserGuide.html">Flume</a>

## Pacotes
<a href="https://github.com/jcpsantos/case_nyc_taxi_trips/blob/master/requirements.txt">Requirements</a>
```
$ pip install -r requirements.txt
```

## Código
Em toda analise foi utilizado o **Spark 2.4.5**, na parte de visualização foi utiliza a biblioteca <a href="https://plotly.com/python/">Plotly</a>, 
na parte de simulação de streaming de dados foi utilizado o **Spark Streaming** em conjunto com o  **Kafka 2.2** e o 
**Flume 1.9** utilizando o package <a href="https://mvnrepository.com/artifact/org.apache.spark/spark-streaming-kafka-0-8_2.11/2.2.0">Spark-Streming-Kafka</a>

- <a href="https://github.com/jcpsantos/case_nyc_taxi_trips/blob/master/case_datasprints.ipynb">Notebook</a>
