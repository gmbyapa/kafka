# kafka

### read offset topic
./kafka-console-consumer --topic "__consumer_offsets" --formatter "kafka.coordinator.group.GroupMetadataManager\$OffsetsMessageFormatter" --consumer.config myconfig --bootstrap-server "192.168.180.107:9092" --offset 6866132 --partition 23  --max-messages 10000
