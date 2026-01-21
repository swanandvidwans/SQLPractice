Normalization - 

Database normalization is a systematic process in a relational database design used to organize tables and fields to:
1. Minimize Redundency
2. Reduce Dependency
3. Ensure data consistency, integrity and efficiency

Redundency in databases - 
Redundency in a database occurs when the same piece of data is stored in multiple places.

Types of Redundency:
1. Unintentional Redundency - Arises due to poor database design, where the same data point appears across various tables or within the same table multiple times.
2. Intentional Redundency - Used deliberately for certain scenarios. Like improving read performance, by replicating data in a way that reduces complex joins.

Problems with Redundencies:
1. Wasted Storage
2. Data Inconsistency
3. Increased Maintainance cost
4. Decreased perofrmance

Anomalies in Databases:
1. Insertion Anomaly
2. Update Anomaly
3. Deletion Anomaly

Types of Database Normal Forms:
1NF, 2NF, 3NF, BCNF

1 - Atomicity
2 - No Partial Dependency
3 - No Transitive Dependency
