# Read Replicas vs Cross region Read Replicas

Read replica are a great way to scale horizontally for high availability in a read-heavy workloads. Lets say you have a database where the traffic request coming to the database are more of read request than write request, creating a read replica database will reduce the workload on the primary database.

Read replicas are copied asynchronously from your primary database, you route queries to the read replica to reduce the workload off a single database.


<img width="1123" alt="Screenshot 2023-08-31 at 16 24 00" src="https://github.com/McTello/Read-Replica-vs-Cross-Region-Replicas/assets/89931817/dad41911-45bf-4c1c-86a9-66f4218f754d">



With Amazon RDS, you can create a MariaDB, Aurora MySQL, MySQL, Oracle or PostgreSQL read replica in different region from the source database instance. Creating a cross-region read replica is noe supported fro SQL server on Amazon RDS.


<img width="1093" alt="Screenshot 2023-08-31 at 16 37 19" src="https://github.com/McTello/Same-Region-Read-Replica-vs-Cross-Region-Replicas/assets/89931817/14a17fc8-4ab7-4c2d-b42b-cfe969466c74">

