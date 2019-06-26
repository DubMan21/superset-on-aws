# Deploy superset on an EC2 AWS.

### 1. Create an instance EC2

+ First, on AWS console go to the **EC2** service's **instance** section and click on **launch an instance**.

+ Then, select an **Ubuntu Server 18.04 LTS** instance.

![Ubuntu Server 18.04 LTS](https://github.com/DubMan21/superset-on-aws/blob/master/img/ubuntu-server.png "Ubuntu Server 18.04 LTS")  

+ Choose an instance type.
> If you do not want paid, choose t2.micro.

![t2.micro](https://github.com/DubMan21/superset-on-aws/blob/master/img/instance-type.png "t2.micro")

+ Go to tab **6.Configure the security group** to add HTTP and HTTPS protocols.

![instance protocols](https://github.com/DubMan21/superset-on-aws/blob/master/img/ports.png "instance protocols")  

+ Finally click on **Check and launch** button then on **Lanch** and create and download a new key pair.
After a few minutes the server should be running

> You can see it on the **EC2** service's **instance** section.
> When you select it, you can see all its parameters
> The most importants are DNS and IP publique.

![Runnig server](https://github.com/DubMan21/superset-on-aws/blob/master/img/running-server.png "Runnig server")

### 2. Connect to the instance

+ First select the instance and click on **Connexion**. Then, follow the instructions to connect to your EC2 with SSH protocol.

![Connection instructions](https://github.com/DubMan21/superset-on-aws/blob/master/img/connexion.png "Connection instructions")

After that, you will be connected to your EC2 as ubuntu user.

![SSH connection](https://github.com/DubMan21/superset-on-aws/blob/master/img/terminal.png "SSH connection")

