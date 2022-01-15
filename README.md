## GoAround 



GoAround is a full-stack web application for users to share photos and videos and publish posts. The frontend is created with React, and the backend is developed using *Go*. 

Launched a scalable web service in *Go* to handle user posts and account information. Deployed to *Google Cloud (Google App Engine)* for autoscaling.

Utilized ElasticSearch (GCE) to provide geo-location based search functions such that users can search nearby posts within a distance (e.g., 200km)

Used Google Dataflow to implement a daily dump of posts to BigQuery table for offline analysis

Aggregated the data at the post level and user level to improve the keyword-based spam detection (BigQuery)



### Architecture

<p align="center"><img src="img/web-architecture.png" alt="Project Architecture"></p>
