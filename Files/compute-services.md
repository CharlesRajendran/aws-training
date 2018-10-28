- #### [AWS EC2](https://github.com/CharlesRajendran/aws-training/blob/master/Files/aws-ec2.md)
  - Allow us to create server instances
  <div align="center"><img src="https://github.com/CharlesRajendran/aws-training/blob/master/images/14.png" /></div>

- #### [EC2 Autoscaling](https://github.com/CharlesRajendran/aws-training/blob/master/Files/aws-auto-scaling.md)
  - There are two types of auto scaling
    - Vertical scaling : 
      - An instance will be replaced with larger server instance.
      - Problem with this type of scaling is, it will take some time to move from one server to another, also moving back and forth will make it ineffective.
      
    - Horizontal scaling: 
      - This will add more equal instances to handle huge amount of traffic.
      - When it comes to horizontal scaling, we will have multiple instances handling the requests, so it is important to have one common endpoint expose to the world. this is where aws load balancers come in handy.
        <div align="center"><img src="https://github.com/CharlesRajendran/aws-training/blob/master/images/15.png" /></div>

      - ##### Load Balancers: This will distribute the traffic among the server instances in the auto scaling group.
        <div align="center"><img src="https://github.com/CharlesRajendran/aws-training/blob/master/images/16.jpeg" /></div>
  - Auto scalers will do health checks and if some instances down then it will replace with new instance.

- #### [Amazon Lightsail](https://github.com/CharlesRajendran/aws-training/blob/master/Files/aws-light-sail.md)
  - Low cost, light weight infratructure offering service.
  - This has less features compare to EC2
  - Quick way to launch servers, with storage and dns management.
  
- #### [Amazon ECS](https://github.com/CharlesRajendran/aws-training/blob/master/Files/aws-ecs.md)
  - This is a container deployment service to deploy docker containers.
  <div align="center"><img src="https://github.com/CharlesRajendran/aws-training/blob/master/images/17.jpeg" /></div>
  
- #### [Amazon Lamda](https://github.com/CharlesRajendran/aws-training/blob/master/Files/aws-lambda.md)
  - A serverless service
  - Funtions as a Service
  
  <div align="center"><img src="https://github.com/CharlesRajendran/aws-training/blob/master/images/18.jpg" /></div>      
