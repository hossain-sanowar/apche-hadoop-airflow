# pyspark-hadoop-pipeline

#1. pull docker file spark-hadoop-airflow
```
docker pull avnish327030/spark-hadoop-airflow
```
#2. Rename pulled docker image
```
docker image tag  avnish327030/spark-hadoop-airflow spark-hadoop-airflow
```
#3. To run the docker image
```
docker run -it -p 9870:9870 -p 8088:8088 -p 8080:8080 -p 18080:18080 -p 9000:9000 -p 8888:8888 -p 9864:9864 -p 8085:8085 -p 8793:8793 -p 8081:8081 -v /Users/mdsanowarhossain/Documents/Project_Pro/BIGDATA\notebook:/root/ipynb -v /Users/mdsanowarhossain/Documents/Project_Pro/BIGDATA\airflow:/home/airflow -v /Users/mdsanowarhossain/Documents/Project_Pro/BIGDATA\data:/data spark-hadoop-airflow

```
# 4. 
