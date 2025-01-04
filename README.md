# real_time_event_processing_pipeline
This project achieves realtime event processing pipeline using Kafka, Pyspark, Dynamo DB and integrates AWS<br/><br/>
--------Setting Up Kafka on localhost------------------<br/>
**Guide to implementing this project.**<br/>
Setup Kakfa and Test run Producer and consumer.<br/>
Test PySpark inegration.<br/>
Implement the event processing using Kafka, PySpark.<br/>
Integrate AWS and Dockerize.<br/><br/>
Setting Up Kafka - <url>https://medium.com/@bectorhimanshu/setting-up-installing-and-starting-the-kafka-server-on-macos-7d505e32039a<br/><br/>
Downloaded and Extracted Kafka<br/>
Started Zookeeper and Kafka Server<br/>
Created a sample Topic<br/>
Started console producer and added messages<br/>
Started console consumer and read/consumed all messages from beginning<br/>
---------Setup and Testing Complete on Localhost-----------

**Project Arcitecture**<br/>
Stock market Dtaset(Producer) -> Kafka -> S3 -> Crawler -> Glue Catalog -> Amazon Athena<br/>
1. Setup EC2 Instance with all basic preoperties pre defined by AWS
2. Setup and Download the .pem Keypair and secure the file on local machine and elevator permissions (tip chmod 400)
3. Login to EC2 instance using SSH (select yes)
4. Install Kafka, Zookeeper using "wget" command
