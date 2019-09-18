# kafkaVSsynctool
kafkaVSsynctool

# Run
    1. brew install pkg-config
    2. brew install librdkafka
    3. cd docker  && docker-compose up -d
    4. cd ./services/kafka-broker && go run main.go
    5. cd ./services/kafka-consumer && go run main.go
    6. get postman collection https://www.getpostman.com/collections/5dc56e98a04c875513c5
    7. make request from postman endpoint