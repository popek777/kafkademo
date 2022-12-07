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

# build kafkademo app
./build.sh

# run denmo app producing messages (taken completly from official example https://github.com/edenhill/librdkafka/blob/master/examples/producer.cpp)
./build/bin/kafkademo localhost:9092 quickstart

