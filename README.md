# docker
docker run -u $(id -u) -p 8090:8080 -p 4045:4040 --rm -v /mnt/data/app/spark:/opt/spark -e SPARK_HOME=/opt/spark  --name zeppelin apache/zeppelin:0.10.1