# Getting Started with MongoDB Atlas

## Lesson 01: Introduction to MongoDB Atlas, the Developer Data Platform

- Which of the following is something that you can do with MongoDB Atlas? (Select all that apply.)
Correct Answer:

  - A. Store your data with MongoDB's multi-cloud, global service.Your Answer: Correct
  Correct.

  - The database is the core of MongoDB's developer data platform. It is a multi-cloud database service built for resilience, scale, and the highest levels of data privacy and security.

  - B. Add search functionality to your application, like a search bar.Your Answer: Correct
  Correct!

    MongoDB Atlas Search is an embedded full-text search that gives you a seamless, scalable experience for building relevance-based app features.

  - C. Write and host a full application in a managed cloud environment.Your Answer: Correct
  Correct.

    Application Services are cloud services that simplify building applications with Atlas.

  - D. Query across multiple Atlas clusters to get a holistic view of your data.Your Answer: Correct
  Correct.

  Data Federation allows you to natively query, transform, and move data across AWS S3 and MongoDB Atlas clusters.

- Which of the following statements are true about MongoDB Atlas Clusters? (Select all that apply.) Correct Answer:

  - A. A MongoDB Atlas Cluster is a group of servers that are connected via a network that hold copies of your data.Your Answer: Correct
Correct.  

    MongoDB Atlas Clusters are used to store copies of your data.

  - B. Once you set up and configure your MongoDB Atlas Cluster, you cannot make any changes to cloud-provider, region, or cluster tier.
  Incorrect.

    One of the advantages to using a MongoDB Atlas Cluster is that the configuration can change as your needs evolve. If you find that you need to add a region or move to a different cluster tier, those changes can be made easily!

  - C. MongoDB Atlas Clusters can be deployed globally in a single geographical region or across multiple geographical regions, depending on the cluster tier.Your Answer: Correct
  Correct.

    Free and shared clusters can be deployed in a single geographical region, while dedicated clusters can be deployed across multiple geographical regions.

  - D. Dedicated clusters provide access to all Atlas features.Your Answer: Correct 
  Correct!

    M10+ dedicated clusters provide access to all Atlas features.

## Lesson 02: Creating and Deploying an Atlas Cluster

- Good Practice:

  - Create a new project for each new application you build. This will help you keep your applications organized and make it easier to manage your Atlas resources.

  - When creating a new cluster, you can choose to deploy a free cluster or a paid cluster. Free clusters are great for testing and development, but they are not recommended for production environments.

User: jovicon
Pass: IKQUfaqS2k4JyQBn

```bash
$> ~ atlas auth register
# 4TMH-3PDC -- Copy this to your account
```

## Conclusión
In this unit, you learned that MongoDB Atlas is a developer data platform that stores your data in Atlas clusters, a global, multi-cloud database service. You also learned that the developer data platform has many features that enable you to build a wide variety of applications.

- You created a free Atlas account and deployed a free tier Atlas cluster by doing the following:
  - Chose a shared cluster.
  - Chose a major cloud provider to host your cluster.
  - Used the region recommended by MongoDB as the location of database deployment.
  - Prepared to connect to your cluster by adding a database user and password and an IP address to the IP Access list

Finally, you successfully loaded sample data into your cluster and found a document in a collection by using Data Explorer.

Resources
Use the following resources to learn more about inserting and finding documents in MongoDB:

- Lesson 01: Introduction to MongoDB Atlas, the Developer Data Platform
  - [MongoDB Docs: MongoDB Clusters](https://www.mongodb.com/basics/clusters?_ga=2.214898071.1696183875.1693764839-1882492524.1682093535)
  - [MongoDB Docs: MongoDB Atlas](https://www.mongodb.com/docs/atlas/?_ga=2.214898071.1696183875.1693764839-1882492524.1682093535)

- Lesson 02: Creating and Deploying an Atlas Cluster
  - [MongoDB Docs: Get Started with Atlas](https://www.mongodb.com/docs/atlas/getting-started/?_ga=2.256717451.1696183875.1693764839-1882492524.1682093535)
  - [MongoDB Docs: Deploy a Free Cluster](https://www.mongodb.com/docs/atlas/tutorial/deploy-free-tier-cluster/?_ga=2.256717451.1696183875.1693764839-1882492524.1682093535)
  - [MongoDB Docs: Load Sample Data](https://www.mongodb.com/docs/atlas/sample-data/?_ga=2.256717451.1696183875.1693764839-1882492524.1682093535)
