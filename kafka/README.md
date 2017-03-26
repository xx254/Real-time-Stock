Description:
Mock the real-time stock price Kafka producer
	
Procedure:
1. Start Kafka on Docker
2. Start consumer in Kafka console:  
	```./kafka-console-consumer.sh --zookeeper `docker-machine ip bigdata`: 2181 --topic stock-analyzer```
3. Start Producer using the library in kafka:  
	```javac -cp "/Users/myname/kafka/libs/*" Producer.java```  
	```java -cp .:"/Users/myname/kafka/libs/*" Producer```