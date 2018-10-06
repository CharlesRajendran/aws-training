- #### [AWS EC2](https://github.com/CharlesRajendran/aws-training/blob/master/aws-ec2.md)
  - Allow us to create server instances
<div align="center"><img src="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/images/overview_getting_started.png" /></div>

- #### [EC2 Autoscaling](https://github.com/CharlesRajendran/aws-training/blob/master/aws-auto-scaling.md)
  - There are two types of auto scaling
    - Vertical scaling : 
      - An instance will be replaced with larger server instance.
      - Problem with this type of scaling is, it will take some time to move from one server to another, also moving back and forth will make it ineffective.
      
    - Horizontal scaling: 
      - This will add more equal instances to handle huge amount of traffic.
      - When it comes to horizontal scaling, we will have multiple instances handling the requests, so it is important to have one common endpoint expose to the world. this is where aws load balancers come in handy.
        <div align="center"><img src="http://www.pc-freak.net/images/horizontal-vs-vertical-scaling-vertical-and-horizontal-scaling-explained-diagram.png" /></div>

      - ##### Load Balancers: This will distribute the traffic among the server instances in the auto scaling group.
        <div align="center"><img src="https://cdn-images-1.medium.com/max/751/1*XLbYqFVdgaoJdrAmSYvp4Q.jpeg" /></div>
  - Auto scalers will do health checks and if some instances down then it will replace with new instance.

- #### [Amazon Lightsail](https://github.com/CharlesRajendran/aws-training/blob/master/aws-light-sail.md)
  - Low cost, light weight infratructure offering service.
  - This has less features compare to EC2
  - Quick way to launch servers, with storage and dns management.
  
- #### [Amazon ECS](https://github.com/CharlesRajendran/aws-training/blob/master/aws-ecs.md)
  - This is a container deployment service to deploy docker containers.
  <div align="center"><img src="https://cdn-images-1.medium.com/max/1600/1*rnarETkxD7_yNCO3GNfDPg.jpeg" /></div>
  
- #### [Amazon Lamda](https://github.com/CharlesRajendran/aws-training/blob/master/aws-lambda.md)
  - A serverless service
  - Funtions as a Service
  
  <div align="center"><img src="https://i2.wp.com/blog.rambabusaravanan.com/wp-content/uploads/2017/06/send-smtp-email-using-aws-lambda.jpg?resize=791%2C391" /></div>      
