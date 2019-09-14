# Designing Cloud Applications Requires Different Mindset
> There are several factors you'll need to consider when designing your cloud application:

- Clients 
> previously connected to applications through the enterprise's local network, and are now often required to connect over the public internet. The public internet will introduce increased latency, reduced bandwidth, and is less reliable.

- Demand
>  on the application was relatively small and stable, and load didn't change very much and was fairly predictable. The demand has become increasingly more dynamic with much larger loads on applications.

- Datacenters
>  generally served a single tenant or enterprise, and are now serving multiple tenants. The multitenant environment comes with its own set of challenges, such as the “noisy neighbor problem.” The application may be sharing resources, like network or physical disks. Although they are isolated, load from one may potentially impact the other.

- Operations
>  required a large number of highly specialized people. Everything from the physical space to power, HVAC, networking, server hardware, and operating system required staff to manage it. These things can be managed through an API in the cloud, and automation can be used to provide reliability and reduce operational overhead.

- Scale
>  was handled by increasing the resources in very expensive and specialized hardware (scale up). In the cloud, this is achieved by distributing the load across a larger number of commodity machines (scale out).

- Failure
>  was less likely, and was managed through the use highly specialized hardware. Cloud applications, however, are built on commodity hardware that is more likely to fail.

- Machine loss
>  was a catastrophic event. Losing a single machine often meant that the application was not available and prevented the business from continuing operation until it was repaired. Machine loss is expected with cloud applications, and they are designed to be resilient to these conditions.

> A different approach is required when architecting cost effective and performant applications for the cloud that are resilient to failures.

 