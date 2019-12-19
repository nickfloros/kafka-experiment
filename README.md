# kafka-experiment
A message queue experiment with Kafka

## kafka docker
A good article to create to kafka deployment can be found in 
[here](https://itnext.io/how-to-install-kafka-using-docker-a2b7c746cbdc)

alternative implementation [here](https://github.com/simplesteph/kafka-stack-docker-compose)

kafka-docker-compose is a simple script that starts a single kafka and zookeper instance.

To run kafka for the experiment run the following
```bash
docker-compose -f kafka-docker-compose.yaml up -d
```

To shutdown kafka
```bash
docker-compose -f kafka-docker-compose.yaml down
```

### docker with nodejs and oracledb client
https://github.com/CollinEstes/docker-node-oracle
