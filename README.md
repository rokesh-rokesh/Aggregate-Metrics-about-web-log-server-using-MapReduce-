**Project: Weblog Data Analysis using MapReduce on Single-Node Hadoop Cluster**

In this project, I developed a MapReduce application in Java to analyze the NASA weblog dataset, a real-world and sizeable dataset. By harnessing the power of Hadoop's MapReduce framework, I calculated essential aggregate metrics from the dataset on a single-node Hadoop cluster.

**Dataset Acquisition:** I obtained the NASA weblog dataset, a comprehensive log of web requests, which included details such as IP addresses, timestamps, request methods, URLs, and response codes.

**Hadoop Setup and Configuration:** I configured a single-node Hadoop cluster to simulate a distributed environment on a local machine. This allowed me to take advantage of Hadoop's parallel processing capabilities.

**MapReduce Implementation:** I developed a custom MapReduce application in Java, utilizing the Hadoop MapReduce API. The application included Mapper and Reducer classes to perform data extraction, transformation, and aggregation.

**Data Transformation and Aggregation:** In the Mapper class, I parsed the weblog records, extracted relevant information, and emitted key-value pairs for subsequent processing. The Reducer class aggregated the emitted data to calculate simple metrics such as total requests, unique IP addresses, and request counts per URL.

**Execution and Job Monitoring:** I executed the MapReduce job on the Hadoop cluster and monitored its progress through the Hadoop JobTracker web interface. The application efficiently processed the dataset by distributing the workload across map and reduce tasks.

**Metrics and Reporting:** The application generated insightful reports containing the calculated metrics, shedding light on web traffic patterns and resource utilization. These metrics provided valuable insights for further analysis and decision-making.
