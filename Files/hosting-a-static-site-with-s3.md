## Hosting a static website
### Planning Steps
1. Purchasing Website with `AWS Route53`
2. Deploy the code files as `s3` object to a `s3` bucket
3. Enable web hosting in `s3`
4. Create `cloudfront distribution` to host the files into edge location for quick access
5. Use `Route53` Service to control the DNS Mapping for all the edge locations
6. Enable SSL Encryption using `AWS Certificate Manager`
![Planing](https://github.com/CharlesRajendran/aws-training/blob/master/images/StaticSiteHosting-S3/1.JPG)
<hr>

### Workflow
![Image2](https://github.com/CharlesRajendran/aws-training/blob/master/images/StaticSiteHosting-S3/2.JPG)
<hr>

