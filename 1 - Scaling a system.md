
## Vertical scaling

In a simple system consisting of a single server, users from various devices access the server over the internet. Typically, this setup is sufficient to handle all incoming requests, and occasional traffic spikes causing downtime may not be a major concern. If the volume of requests increases, you can upgrade your server to a more powerful one -albeit at a higher cost- to handle the additional load. Similarly, if your server interacts with a database, you might rely on a single database instance to handle all reads and writes. As with the server, you could upgrade the database instance to one with greater capacity or performance when needed.

This approach of improving your infrastructure by replacing resources with larger, more capable ones is known as **vertical scaling**. It is the go-to solution for small infrastructures because it is simple, efficient, and relatively cost-effective.

However, vertical scaling has its limitations. As your system continues to grow, you may eventually hit physical or practical constraints, where upgrading a single server or database instance is no longer feasible. At this point, you would need to introduce additional servers, replicate your database, and scale your services horizontally to handle the growing demands.


## Horizontal scaling


## Vertical vs Horizontal scaling
