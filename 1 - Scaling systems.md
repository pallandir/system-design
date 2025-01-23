
## Vertical scaling

In a simple system consisting of a single server, users from various devices access the server over the internet. Typically, this setup is sufficient to handle all incoming requests, and occasional traffic spikes causing downtime may not be a major concern. If the volume of requests increases, you can upgrade your server to a more powerful one -albeit at a higher cost- to handle the additional load. Similarly, if your server interacts with a database, you might rely on a single database instance to handle all reads and writes. As with the server, you could upgrade the database instance to one with greater capacity or performance when needed.

This approach of improving your infrastructure by replacing resources with larger, more capable ones is known as **vertical scaling**. It is the go-to solution for small infrastructures because it is simple, efficient, and relatively cost-effective.

However, vertical scaling has its limitations. As your system continues to grow, you may eventually hit physical or practical constraints, where upgrading a single server or database instance is no longer feasible. At this point, you would need to introduce additional servers, replicate your database, and scale your services horizontally to handle the growing demands.

## Horizontal scaling

When your system grows to the point where multiple servers and database instances are necessary to handle thousands or even millions of transactions and users, scaling horizontally becomes essential. This approach distributes incoming requests across multiple servers, solving availability and capacity issues. However, it introduces added complexity in maintenance and comes at a higher cost.

The key advantage of horizontal scaling is that it removes physical limitations. With this setup, accommodating another million users is as simple as adding more servers—budget permitting.

This process of adding servers and/or databases in parallel is called **horizontal scaling**. While it requires a larger investment and more effort to manage, it enables virtually unlimited scalability to meet the growing demands of your service.

## Vertical vs Horizontal scaling

As illustrated below, **vertical scaling** involves enhancing the capabilities of an existing system by adding more resources, such as upgrading the hardware (e.g., CPU, RAM, or storage) of a single server or database instance. In contrast, **horizontal scaling** expands the system by adding more servers or database instances to the infrastructure, effectively distributing the workload across multiple systems. This distinction captures the core difference between the two approaches to scaling.

![scaling](./resources/scaling.png|304)