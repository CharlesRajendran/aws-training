## Amazon Route 53 ([Documentation](https://aws.amazon.com/route53/))
- Amazon Route 53 is a highly available and scalable cloud Domain Name System (DNS) web service.

- Amazon Route 53 effectively connects user requests to infrastructure running in AWS, such as,
  - Amazon EC2 instances, 
  - Elastic Load Balancing load balancers
  - Amazon S3 buckets 
  - Also be used to route users to infrastructure outside of AWS.

- You can use Amazon Route 53 to configure DNS health checks to route traffic to healthy endpoints or to independently monitor the health of your application and its endpoints.

- Integrating `Amazon Route 53` with `AWS Identity and Access Management (IAM)`, you can grant unique credentials and manage permissions for every user within your AWS account and specify who has access to which parts of the `Amazon Route 53 service`.
<hr>

### `Amazon Route 53 Traffic Flow` 
- this service makes it easy for you to route your site traffic globally through a variety of routing types Including,
  - Latency Based Routing 
  - Geo DNS 
  - Geoproximity 
  - Weighted Round Robin
- `Amazon Route 53 Traffic Flow` routes traffic based on multiple criteria, such as endpoint health, geographic location, and latency.

- Using `Amazon Route 53 Traffic Flow`’s simple `visual editor`, you can easily manage how your end-users are routed to your application’s endpoints—whether in a single AWS region or distributed around the globe.

- You can configure multiple `traffic policies` and decide which policies are active at any given time.   

- You can create and edit `traffic policies` using the simple visual editor in the `Route 53 console`, `AWS SDK`s, or the `Route 53 API`. 
  
  - `Traffic Flow`’s `versioning feature` maintains a history of changes to your traffic policies, so you can easily roll back to a previous version using the console or API.

- Amazon Route 53 is backed by the [Amazon Route 53 Service Level Agreement](https://aws.amazon.com/route53/sla/).
<hr>

### Domain Name Registration With Route53
- Amazon Route 53 also offers Domain Name Registration – you can purchase and manage domain names
- Amazon Route 53 will automatically configure DNS settings for your domains.
<hr>

### Amazon Route 53 features ([Goto](https://aws.amazon.com/route53/features/))
