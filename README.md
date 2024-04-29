# Apache Kafka with Zookeeper 
Apache Kafka is great for messaging, storage, and stream processing. It is massively scalable because it allows data to be distributed across multiple servers, and it's extremely fast because it decouples data streams, which results in low latency. It can also distribute and replicate partitions across many servers, which protects against server failure.So why we should use Kafka?
- High throughput
- Fault tolerant
- Scalable
## Kafka Architecture
<img width="800" alt="Screenshot 2024-04-29 at 3 40 54 PM" src="https://github.com/Ibodullaev/kafka-cab-booking-between-driver-user/assets/33604928/e9a50357-2e1b-426e-9971-358be9bac25a">        

## Project Architecture
So It has two modules named driver and user respectively. Driver sends the data to user its live location in every second. For messaging between microservice user and driver I have used kafka messaging for live location notifications. 
