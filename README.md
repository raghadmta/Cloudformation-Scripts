# Cloudformation-Scripts

### [website-deploy.yaml](https://github.com/raghadmta/Cloudformation-Scripts/blob/aab0bd3800d9dbc17819af605ddbc3736d0422ad/website-deploy.yaml) 
cloudformation stack thats create a custom VPC, two ec2 servers, two security groups, bootstrap apache2 server with default page 
and it will be publicly accessible.

</br>

---

### [ec2-instance.yaml](https://github.com/raghadmta/Cloudformation-Scripts/blob/aab0bd3800d9dbc17819af605ddbc3736d0422ad/ec2-instance.yaml) 
cloudformation stack with default IP 0.0.0.0 allow only standard IP format, allow only t2.nano, t2.micro, t2.small, t2.medium instances, public port 80 access but port 22 access only from your own IP, one instance of amazon linux Latest AMI of amazon linux taken as 
parameter and output AZ, DNS, public IP
</br>

---
###### This project was part of Saudi Digital Acadmy's ( SDA ) DevOps  BootCamp 2022 
