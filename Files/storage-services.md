- #### [S3 - Simple Storage Service](https://github.com/CharlesRajendran/aws-training/blob/master/Files/aws-s3.md)
  - S3 is a serverless service which means we don't have to manages the opreational things, aws will manage for us.
  - In S3, we have something call bucket, which can take any type of files or objects.
 
- #### [Amazon Glacier](https://github.com/CharlesRajendran/aws-training/blob/master/Files/aws-glacier.md)
  - Amazon glacier is the cheapest storage service in aws
  - It is used to archive or to keep a backup of your data.
  - Glacier data will note be readyly available, we have to wait like 3-4 hours to get the archived data back.
  - We can have lifecycle rules to store S3 data to have a backup in glacier when the s3 object get aged.
  
<div align="center"><img src ="https://image.slidesharecdn.com/s3-170918104022/95/deep-dive-on-object-storage-amazon-s3-and-amazon-glacier-20-638.jpg?cb=1505737836" /></div>
 
- #### [Amazon EBS - Elastic Block Storage](https://github.com/CharlesRajendran/aws-training/blob/master/Files/aws-ebs.md)
  - It is like a hard drive to the EC2 instances.
  - Readily avaiable and low latency, since it is closely attached to the server instances.
  - Resides inside vpc.
 
<div align="center"><img src ="https://4.bp.blogspot.com/-Zv39LdIQbdE/VwA4noCaTXI/AAAAAAAARxM/ySpqQV8fiS835CIJwVckYHaQXfdCmOxsg/s1600/57.1%2BAmazon%2BElastic%2BBlock%2BStore.png" /></div>

- #### [Amazon EFS - Elastic File Storage](https://github.com/CharlesRajendran/aws-training/blob/master/Files/aws-efs.md)
  - It is a network storage services for ec2 instances
  - Multiple instances can share the efs data source.
  - Resides inside vpc
<div align="center"><img src ="https://geekflare.com/wp-content/uploads/2017/08/aws-efs-diagram.png" /></div>
  
- #### [Storage Gateway](https://github.com/CharlesRajendran/aws-training/blob/master/Files/aws-storage-gateway.md)
  - This is used when we want to have a hybrid storage mechanism, such as having a backup in the cloud for disaster recovery.
  - It will also allow you to have your frequently accessed data in on proimise and all the data in aws, such as in s3 bucket.
  - Storage Gateway will orchastrate the data transmission from aws to on primise and vice versa.
<div align="center"><img src ="https://www.allthingsdistributed.com/images/arch_diagram_storagegateway.png" /></div>

- #### [AWS Snow Ball](https://github.com/CharlesRajendran/aws-training/blob/master/Files/aws-snowball.md)
  - This is a peta byte scale storage device by amazon.
  - This is used when you want to move your inpremise data to the cloud.
  - You will reciece the device from aws, copy you inprimise data to the device and send back to amazon, where they will move the data from the snowball deveice to cloud storage (such as s3)

<div align="center"><img src ="https://github.com/CharlesRajendran/aws-training/blob/master/images/7.JPG" /></div>
  

