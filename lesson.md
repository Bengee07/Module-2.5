## Brief

### Preparation

Write about any preparations needed for the lesson, such as tools, installations, prior-knowledge, etcs.

### Lesson Overview

Developments in cloud technology make it possible to replicate almost any data center activity on hosted infrastructure. So, what is so special about cloud databases? And why should you consider moving to a Database as a Service model?

---

## Part 1 - SQL & NoSQL Database

SQL is a decades-old method for accessing relational databases, and most who work with databases are familiar with it. As unstructured data, amounts of storage and processing power and types of analytics have changed over the years, however, we’ve seen different database technologies become available that are a better fit for newer types of use cases. These databases are commonly called NoSQL.

SQL and NoSQL differ in whether they are relational (SQL) or non-relational (NoSQL), whether their schemas are predefined or dynamic, how they scale, the type of data they include and whether they are more fit for multi-row transactions or unstructured data.


### What is a SQL database?

SQL, which stands for “Structured Query Language,” is the programming language that’s been widely used in managing data in relational database management systems (RDBMS) since the 1970s. In the early years, when storage was expensive, SQL databases focused on reducing data duplication.


Fast-forward to today, and SQL is still widely used for querying relational databases, where data is stored in rows and tables that are linked in various ways. One table record may link to one other or to many others, or many table records may be related to many records in another table. These relational databases, which offer fast data storage and recovery, can handle great amounts of data and complex SQL queries.


### What is a NoSQL database?

NoSQL is a non-relational database, meaning it allows different structures than a SQL database (not rows and columns) and more flexibility to use a format that best fits the data. The term “NoSQL” was not coined until the early 2000s. It doesn’t mean the systems don’t use SQL, as NoSQL databases do sometimes support some SQL commands. More accurately, “NoSQL” is sometimes defined as “not only SQL.”


### How SQL works

SQL databases are valuable in handling structured data, or data that has relationships between its variables and entities.

**- Scalability**

In general, SQL databases can scale vertically, meaning you can increase the load on a server by migrating to a larger server that adds more CPU, RAM or SSD capability. While vertical scalability is used most frequently, SQL databases can also scale horizontally through sharding or partitioning logic, although that’s not well-supported.

**- Structure**

SQL database schema organizes data in relational, tabular ways, using tables with columns or attributes and rows of records. Because SQL works with such a strictly predefined schema, it requires organizing and structuring data before starting with the SQL database.


**- Properties**

RDBMS, which use SQL, must exhibit four properties, known by the acronym ACID. These ensure that transactions are processed successfully and that the SQL database has a high level of reliability:

- Atomicity: All transactions must succeed or fail completely and cannot be left partially complete, even in the case of system failure.
- Consistency: The database must follow rules that validate and prevent corruption at every step.
- Isolation: Concurrent transactions cannot affect each other.
- Durability: Transactions are final, and even system failure cannot “roll back” a complete transaction.

**- Support**

Because SQL databases have a long history now, they have huge communities, and many examples of their stable codebases online. There are many experts available to support SQL and programming relational data.

**Examples of SQL databases**

- MySQL
- PostgreSQL
- YugabyteDB
- CockroachDB
- Oracle Database
- Microsoft SQL Server
- Azure SQL Database

---

## Part 2 - Summary of Database-as-a-service

![image](https://user-images.githubusercontent.com/106639884/188791209-8c801f66-9d24-4ae8-982f-0c6d9c6a43e4.png)


### What is a Database-as-a-service?

Like SaaS, PaaS and IaaS of cloud computing we can consider DBaaS (also known as Managed Database Service) as a cloud computing service. It allows users associated with database activities to access and use a cloud database system without purchasing it.


DBaaS and cloud database comes under Software as a Service (SaaS) whose demand is growing so fast
In simple we can say Database as a Service (DBaaS) is self service/ on demand database consumption coupled with automation of operations. As we know cloud computing services are like pay per use so DBaaS also based on same payment structure like how much you will use just pay for your usage. This DBaaS provides same function as like standard traditional and relational database models. So using DBaaS, organizations can avoid data base configuration, management, upgradation and security.


DBaaS consists of an info manager element, that controls all underlying info instances via API. This API is accessible to the user through a management console, typically an online application, that the user might use to manage and assemble the info and even provision or deprovision info instances.


Database hosting options are available for all database types, including NoSQL, MySQL, and PostgreSQL. MongoDB Atlas is one example of a NoSQL DBaaS service that is easily scalable.


The DBaaS subscription includes everything required to operate a database in the cloud – including database provisioning, licenses, support, and maintenance. Developers can make use of cloud hosted APIs to build out new applications, accessing and manipulating data programmatically. Because of this, DBaaS shares many similarities with other SaaS subscription-based cloud offerings.


As a managed service, there is no additional overhead; you can get right to work extracting value from your data store.


### How Does DBaaS Work?

Once the data has been uploaded, the DBaaS database engine itself operates in almost exactly the same way as an on-premises installation. In fact, the very same core is installed in the hosted data center. For developers, DBAs, and data engineers, the experience is almost indistinguishable from working with a local database.


The major difference is the physical infrastructure on which a cloud database runs. In a public Infrastructure as a Service (IaaS) cloud environment like Microsoft Azure, Amazon Web Services (AWS), Google Cloud Platform (GCP), and MongoDB Atlas, the database engine (and data) is run on a shared hardware platform. This adds the compute power, resource elasticity, and scalability needed to support your growing data stores and processing needs.


### How is Database-as-a-service Different from Database Management?


Cloud database management is often much simpler than traditional on-premises equivalents. The database administration tools themselves are almost identical, allowing you to provision databases quickly and easily on the hosted infrastructure.


The major difference between DBaaS and local deployments is the amount of back-end administration required. Cloud computing principles allow you to offload time-consuming infrastructure administration to the service provider; they are responsible for ensuring the physical and application layers are operational and optimized.


Whether you are an individual developer or operate a team of data engineers and developers, outsourcing infrastructure administration frees you to focus on the data itself, reclaiming time and resources that would normally have been spent on low-level maintenance tasks.


---

## Part 3 - Benefits of Database-as-a-service

Compared to deploying a database management system on-premises, DBaaS offers your organization significant financial, operational, and strategic benefits:

**- Cost savings**

Laying down infrastructure for database management is expensive; scaling it as needed is costly and often wasteful. With DBaaS, your organization pays a predictable periodic charge based on the resources you consume—there’s no need to purchase additional capacity to have on hand for hypothetical future needs.

**- Scalability—up and down**

You can quickly and easily provision additional storage and computing capacity at run time if you need it, and you can scale down your database cluster during non-peak usage times to save cost.

**- Simpler, less costly management**

To manage and maintain a database on-premises, you’d need an in-house administrative team. With DBaaS, the cloud provider manages everything (although you can choose to manage certain aspects yourself if you wish). DBaaS lightens the administrative burden on your existing IT staff and frees them to work on applications and innovation.

**- Rapid development and faster time-to-market**

With an on-premises database system, development teams typically need to request access through IT, a process that can take days or weeks. In contrast, with DBaaS, developers can help themselves to database capabilities and spin up and configure a database that’s ready to integrate with their application in minutes.

**- Data and application security**

Cloud database providers typically offer enterprise grade security, including features like default encryption of data at rest and in-transit and integrated identity and access management controls. Some also meet specific regulatory compliance standards.

**- Reduced risk**

DBaaS offerings from major cloud providers typically include a service-level agreement (SLA) guaranteeing a certain amount of uptime. In the unlikely event that your provider doesn’t meet the requirements stipulated in the SLA, you’ll be compensated for any excess downtime you experience.

**- Software quality**

The major cloud providers offer a wide variety of highly configurable DBaaS options—each preselected for quality, so you won’t have to worry about the wading through hundreds of different databases.


---

## Part 4 - Insert Summary

Insert Instructions
