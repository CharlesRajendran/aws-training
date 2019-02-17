#### What is Elastic BeansTalk?
  - service for deploying and scaling web applications and services developed with Java, .NET, PHP, Node.js, Python, Ruby, Go, and Docker on familiar servers such as Apache, Nginx, Passenger, and IIS.
  - Elastic Beanstalk automatically handles the deployment, from capacity provisioning, load balancing, auto-scaling to application health monitoring. At the same time, you retain full control over the AWS resources powering your application and can access the underlying resources at any time.

#### Creating a Node.JS Application
  - Step 1 - After selecting EB service and press the create app button, then give the basic informations, such as project name, and the type of project and etc.
<div align="center"><img src ="https://github.com/CharlesRajendran/aws-training/blob/master/images/ElasticBeansTalk/1.JPG" /></div>

  - Step 2 - If you click on the `Configure more options` button, it will take you to customize the deployment of the application, here you can informations such as whether you want to a simple deployment or a high availability deployment.
    - `Low Cost` option is what you get for freetier
    - `High Availability` option have information such as the,
      - Database options
      - Capacity - How many instances you need to run (It will create a autoscaling group and also a load balancer)
      - Rolling updates and Deployments - Deployment Options 
        - All at once (When updating the application, it will update all the instances)
        - Rolling a batch at a Time (If there is 20 instances, it will update 18 instance and will keep 2 instance while other instances are updating)
        - Rolling with Additional Batch (This will update every instance, but will create two instances mean time to support the serving)
        - Immutable - Two environments temprorily 
        - Blue - Green (Two environments) 
<div align="center"><img src ="https://github.com/CharlesRajendran/aws-training/blob/master/images/ElasticBeansTalk/2.png" /></div>

- Step 3 - Update necessary Information (In my case I will add a database)
<div align="center"><img src ="https://github.com/CharlesRajendran/aws-training/blob/master/images/ElasticBeansTalk/3.png" /></div>

- Step 4 - That's it crete the application.
<div align="center"><img src ="https://github.com/CharlesRajendran/aws-training/blob/master/images/ElasticBeansTalk/4.JPG" /></div>
  - After creating the application you could certain things created, since I have created the app with `Low Cost` option, it has created a EC2 instance and it has given a url to my application. If I created with `High Availability` options, then you could also see auto scaling groups and load balancers created. Also there will be a s3 bucket created to hold the files of the application.
<div align="center"><img src ="https://github.com/CharlesRajendran/aws-training/blob/master/images/ElasticBeansTalk/5.JPG" /></div>

That's it, then you can see the created application by visiting the url. The sample application will look like some thing in the below image. 
<div align="center"><img src ="https://github.com/CharlesRajendran/aws-training/blob/master/images/ElasticBeansTalk/6.png" /></div>

When deleting the application, all the create services will be removed. make sure to delete, if you are just practicing, otherwise you will endup with a bill.
