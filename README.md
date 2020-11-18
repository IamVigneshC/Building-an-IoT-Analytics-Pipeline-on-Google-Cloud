# Building-an-IoT-Analytics-Pipeline-on-Google-Cloud

Analyze IoT data streams easily with Cloud IoT Core using Cloud Pub/Sub, Cloud Dataflow, and BigQuery.

We will Perform the following:


• Connect and manage MQTT-based devices using Cloud IoT Core (using simulated devices)

• Ingest a stream of information from Cloud IoT Core using Cloud Pub/Sub

• Process the IoT data using Cloud Dataflow

• Analyze the IoT data using BigQuery

The term Internet of Things (IoT) refers to the interconnection of physical devices with the global Internet. These devices are equipped with sensors and networking hardware, and each is globally identifiable. Taken together, these capabilities afford rich data about items in the physical world.

Cloud IoT Core is a fully managed service that allows you to easily and securely connect, manage, and ingest data from millions of globally dispersed devices. The service connects IoT devices that use the standard Message Queue Telemetry Transport (MQTT) protocol to other Google Cloud data services.

Cloud IoT Core has two main components:

• A device manager for registering devices with the service, so you can then monitor and configure them
• A protocol bridge that supports MQTT, which devices can use to connect to Google Cloud

Refer: https://iamvigneshc-mydigitalworld.blogspot.com/2020/11/building-iot-analytics-pipeline-on.html


## Data Flow:

![Image of CloudBuild](https://github.com/IamVigneshC/Building-an-IoT-Analytics-Pipeline-on-Google-Cloud/blob/main/streaming%20workflow.PNG)


## IOT Device Simulator running Python code and ingest data into table

![Image of CloudBuild](https://github.com/IamVigneshC/Building-an-IoT-Analytics-Pipeline-on-Google-Cloud/blob/main/IOT_Device_Simulator.PNG)


## BigQuery table data

![Image of CloudBuild](https://github.com/IamVigneshC/Building-an-IoT-Analytics-Pipeline-on-Google-Cloud/blob/main/Data%20ingested%20into%20table.PNG)


