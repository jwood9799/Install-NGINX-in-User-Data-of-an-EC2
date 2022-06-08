# Intall-NGINX-in-User-Data-of-an-EC2

#!/bin/bash

yum update -y

amazon-linux-extras install nginx1.12

systemctl start nginx

systemctl enable nginx 
