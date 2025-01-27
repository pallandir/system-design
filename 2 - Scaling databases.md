As we continue our journey into scaling systems and infrastructure, it’s crucial to examine strategies specifically designed for scaling databases.


In the previous course, [[1 - Scaling systems]], we explored how servers often interact with databases and discussed ways to ensure that servers don’t become a single point of failure in our architecture. But what happens when the database itself becomes the bottleneck? How can we ensure that databases are scalable, resilient, and not a single point of failure in our system?

In this section, we’ll focus on techniques to scale databases effectively and integrate them into a robust, scalable infrastructure.

## Sharding databases

**Sharding** a database is the process of dividing a large table into smaller, more manageable pieces called **partitions** or **shards**. These shards can either retain the original schema and simply be divided into smaller subsets of data or adopt a different schema to split the original table into distinct sub-datasets. This technique is often used to improve performance and scalability by distributing the workload across multiple database instances.

![sharding databases](./resources/sharding_databases.png)