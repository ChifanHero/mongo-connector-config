# mongo-connector-config
1. Make config change
2. login to ec2 machine and pull the config change
3. copy config.json to /etc/mongo-connector.json
4. stop mongo-connector `sudo service mongo-connector stop`
5. delete oplog.timestamp if you want to reindex all documents
6. restart mongo-connector `sudo service mongo-connector start`
