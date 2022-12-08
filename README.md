# kafkademo

kafka demo

# install kafka docker image
https://developer.confluent.io/quickstart/kafka-docker/?build=apps#5-read-messages-from-the-topic

# start kafka broker
docker compose up -d

# create kafka topic
https://developer.confluent.io/quickstart/kafka-docker/?build=apps#3-create-a-topic

# run kafka consumer in docker
https://developer.confluent.io/quickstart/kafka-docker/?build=apps#5-read-messages-from-the-topic

Note:
you may also run full demo app (based on https://github.com/edenhill/librdkafka/blob/master/examples/rdkafka_example.cpp)
in consumer mode to consume messages:

./build/bin/kafkafulldemo -C -t quickstart -b localhost -f ccb -p 

# build kafkademo app
./build.sh

# run denmo app producing messages
 
 demo app based on official example https://github.com/edenhill/librdkafka/blob/master/examples/producer.cpp
 
./build/bin/kafkademo localhost:9092 quickstart

