# Kafka 
    
    docker-compose up 
    docker pull ezguv/kafka
    docker pull ezguv/zookeeper
    docker exec –it kafka /bin/sh
    cd opt/kafka_version/bin/
    kafka-topics.sh –create –zookeeper zookeeper:2181 –replication-factor 1 –partitions 1 –topic first_kafka_topic 
    docker-compose –f docker-compose.yml up –d

