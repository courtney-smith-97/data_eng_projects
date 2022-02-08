# Project 2: Tracking User Activity

In this project, you work at an ed tech firm. You've created a service that
delivers assessments, and now lots of different customers (e.g., Pearson) want
to publish their assessments on it. You need to get ready for data scientists
who work for these customers to run queries on the data. 

# Tasks

This project goes through how to:

- Publish and consume messages with Kafka
- Use Spark to transform the messages. 
- Use Spark to transform the messages so that you can land them in HDFS

The `docker-compose.yml` used for spinning the pipeline is included. Step-by-step instructions for ingesting and transforming the data are included in the Project_2.ipynb file.

The history of the console is in
```
history > courtney-smith-97-history.txt
```

I ran spark using a notebook so there is no separate spark history file.


## Data

```
curl -L -o assessment-attempts-20180128-121051-nested.json https://goo.gl/ME6hjp`
```


The notebook answers the following:

1. How many distinct exams were taken?
2. What are the five most common exams?
3. What is the average score of the five most common exams?


## Files submitted

- courtney-smith-97-history.txt 
- docker-compose.yml
- Project_2.ipynb

---
