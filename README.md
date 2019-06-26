# Deploy superset on an EC2 AWS.

+ First, on AWS console go to the **EC2** service **instance** section and click on **launch an instance**.

+ Then, select an **Ubuntu Server 18.04 LTS** instance.

![Ubuntu Server 18.04 LTS](https://github.com/DubMan21/superset-on-aws/blob/master/img/ubuntu-server.png "Ubuntu Server 18.04 LTS")  

+ Choose an instance type.
> If you do not want paid, choose t2.micro.

![t2.micro](https://github.com/DubMan21/superset-on-aws/blob/master/img/instance-type.png "t2.micro")

+ Go to tab **6.Configure the security group** to add HTTP and HTTPS protocols.

![instance protocols](https://github.com/DubMan21/superset-on-aws/blob/master/img/ports.png "instance protocols")  

+ Finally click on **Check and launch** button, then on **Lanch**.
After a few minutes the server should be running

> You can see it on the **EC2** service **instance** section
