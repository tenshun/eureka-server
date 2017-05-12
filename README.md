# eureka-server

## What is Eureka?

> Eureka is a REST (Representational State Transfer) based service that is primarily used in the AWS cloud for locating services for the purpose of load balancing and failover of middle-tier servers. We call this service, the Eureka Server. Eureka also comes with a Java-based client component,the Eureka Client, which makes interactions with the service much easier. The client also has a built-in load balancer that does basic round-robin load balancing. At Netflix, a much more sophisticated load balancer wraps Eureka to provide weighted load balancing based on several factors like traffic, resource usage, error conditions etc to provide superior resiliency.

## When should I use Eureka?
> You typically run in the AWS cloud and you have a host of middle tier services which you do not want to register with AWS ELB or expose traffic from outside world. You are either looking for a simple round-robin load balancing solution or are willing to write your own wrapper around Eureka based on your load balancing need. You do not have the need for sticky sessions and load session data in an external cache such as memcached. More importantly, if your architecture fits the model where a client based load balancer is favored, Eureka is well positioned to fit that usage.

## Documentation

https://github.com/Netflix/eureka/wiki

