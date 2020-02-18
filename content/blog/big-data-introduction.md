---
title:  "Big data – Introduction"
description:  "What is Big Data? How to analyze it and use it?  Learn more in this blog post!"
author:  "Marko Stojanovic"
cover:  "https://i.imgur.com/Mmhb6rn.jpg"
date:  "2020-02-18"
type:  "post"
---

As my mentor once described Big Data: “Big Data is like teenage sex - everybody is talking about it, but few of them really know what it is”.


## So what is Big Data and why is it important?

Unlike the relatively recent approach where storing data was related to RDBMS (**_relational database management system_**), and if I may say mostly “filtered” in order to store only important things, the main idea behind Big data is the opposite - the more data we store, the more we know. We have the ability to analyze it in order to improve operations, study the habits of a specific group in order to personalize advertising and increase profitability. In other words, we can say that the possibilities are as big as Big data is.


## How “big” is Big Data really?

![](https://simplecore.intel.com/itpeernetwork/wp-content/uploads/sites/38/2018/10/hpc-ai-convergence.jpg)


If we look around, we can see that most people are spending time on digital devices. They’re using it for all sorts of things like business, communication, shopping, information, fun, etc. A common thing in all of the use cases is the constant sharing of large amounts of data, even when they are not used, and we think that the devices are inactive.

With this mind, we come to the conclusion that **2.5 exabytes** of new data are produced in the world daily. Based on some predictions, in 2020 there will be around **40 zettabytes** (**40 trillion gigabytes**) and by 2030 that amount will increase to **88 yottabytes** (**88 quadrillion gigabytes)**.


## Characteristics of Big Data

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/06/Five-Vs-of-Big-Data-What-is-Big-Data-Edureka.png)

This is something that has changed over time and is still in the process of changing. In all cases, it was connected with the letter “V”. It started with three “V’s” and today we are at 5 “V’s”, and who knows, maybe in the future, we will get more “V”s?

- **Value** - refers to transferring data into value. By transferring the accessed big data into value, businesses may generate revenue.

- **Volume** - represents the amount of data that is growing at a high rate ( Petabytes, Exabytes, etc.)

- **Velocity** - the rate at which data grows. Social media has a major role in the velocity of growing data.

- **Variety** - refers to the different data types (text, audios, videos, etc.)

- **Veracity** - refers to the uncertainty of available data. Veracity arises due to the high volume of data that brings incompleteness and inconsistency.


## Types of Big Data

![](https://miro.medium.com/max/2509/1*sBcb7TF8jJwZChdTT_sodw.png)

Now that we have a clearer picture of the size of Big Data, we can classify it in two ways:

The first one is based on the data source:

- **Human-Generated** - this type of data as the name implies is connected to human actions, so it contains all sorts of data like web sites form details, social activity, videos, audios, etc

- **Machine-generated** - this type of data includes transaction data, GPS Tracking, data from IoT sensors, data from medical devices, etc.

The second one is more important and it represents the way of how data is structured:

- **Structured Data** - This type of data is often already stored in databases, mostly in rows and columns where the meaning of each item is defined and can be easily accessed and managed. A rough calculation says that 20% of all existing data makes this group. Some examples of structured data are data received from sensors, financial systems, medical systems, web forms, input data from surveys, etc.

- **Unstructured Data** - This type of data usually represents large datasets and has no clear format in storage. Unlike structured data, that is stored in traditional RDBMS, unstructured data use NoSQL databases like MongoDB, Cassandra, etc. This kind of data didn’t represent a valuable source until recently. However, in the last few years it basically represents “The holy grail” since it can be analyzed and used to extract important information. Examples of unstructured data are social media messages, posts, photos, videos, audio, business presentations, etc.

- **Semi-Structured Data** - As the name says, this type of data combines some properties of structured data which make it easier to read and process, but major part of it is unstructured. Examples of semi-structured data that are most common are e-mails, log files, XML, HTML, etc.


### Types of analysis

![](https://i.pinimg.com/originals/15/07/61/150761af87ffe19153652f5eee3ed8eb.png)

There are 4 types of analytics and based on their complexity and duration, the more value they bring.

- **Descriptive analytics** - this type of analysis answers the question “what happened?” Based on the answer, this type of analytics provides insight into what happened and can provide you with trends in order to dig into more details. The most common examples are all kinds of reports or metrics.

- **Diagnostic analytics** - this type of analysis answers the question “why did something happen?” By combining more data sources, this kind of analysis gives in-depth insights into a particular problem. Examples of this kind of analytics are found in many fields like transportation, system, medicine, etc.

- **Predictive analytics** - this type of analysis answers the question “what is likely to happen?” This type combines Descriptive and Diagnostic analytics in order to predict future trends. Examples of this type of analytics can be found in the retail industry, where it can be predicted what type of stuff a buyer might buy next and when is the best time to put things for sale. The examples can also be found in healthcare where based on a user’s health record, a scientist can predict possible new diseases or similar things.

- **Prescriptive analytics** - this type of analysis answers the question “what action to take?” It represents the most complex analysis type which is based on mathematical modeling. This type of analytics gives the best solution among a variety of choices given the known parameters and suggests options on how to take advantage of a future opportunity or mitigate future risk. An example of using this type of analysis is the suggested route on Google maps, based on traffic jams. Other examples can be also found in medicine, transportation etc.

  
### How to analyze it?

![](https://www.adfi-ci.org/news/photos/aadfi_train_22032019110738.jpg)

The most frequently used method for analyzing raw data is **MapReduce**. 
MapReduce allows taking a large data set and performing computation parallelly on multiple computers. We can split MapReduce into two parts:

  

 - **Map** - it processes input data, splitting it into small blocks and assigning it to a mapper for processing

 - **Reduce** - This part combines two stages:

	

	 1. Shuffle - transferring and sorting all data which is processed in mappers

	 2. Reduce - process all data from shuffleing and combining it to a new output set


### Which tools to use?

![](https://www.stockvault.net/data/2016/05/09/196879/preview16.jpg)

The most stable and most frequently used tool for analyzing big data is [Apache Hadoop](https://hadoop.apache.org/). It represents a framework for processing and storing data at a large scale, and like other Apache’s tools, it’s open source. Hadoop can be split into 4 parts:

- [**HDFS**](https://hadoop.apache.org/docs/current/hadoop-project-dist/hadoop-hdfs/HdfsDesign.html) - Hadoop’s distributed file system designed for a very high aggregate bandwidth

- [**YARN**](https://hadoop.apache.org/docs/current/hadoop-yarn/hadoop-yarn-site/YARN.html) - a platform for managing Hadoop's resources and scheduling programs that will run on the Hadoop infrastructure

- [**MapReduce**](https://hadoop.apache.org/docs/current/hadoop-mapreduce-client/hadoop-mapreduce-client-core/MapReduceTutorial.html) - a model for doing big data processing

- The rest of libraries for other modules to use

**Other tools that often work with Hadoop Framework:**

- [**Apache Spark**](https://spark.apache.org/) - one of the most popular tools in this area is Apache Spark, which provides storing a large quantity of data for processing in memory. This type of processing is a hundred times faster than storing it on a disk. Spark uses HDFS, but it can also work with Apache Cassandra or OpenStack Swift. One of Spark’s benefits is that it is easy to install on a single local machine, which makes development and testing easier.

- [**Apache Kafka**](https://kafka.apache.org/) - a distributed streaming platform used to publish and subscribe to streams of records in real-time. The main goal is to bring the reliability of other messaging systems to streaming data.


## Summary

Now that you have a clearer picture of what Big Data is, challenge yourself to dive more into this field. Experiment with various tools, and train your ML models about which you can read in our other [post](https://www.hackbelgrade.com/blog/artificial-intelligence-introduction/). If you do this, trust me - only the sky's the limit :)