# customer-data

PHP Based project 

Step 4: SSH into the instance.

Run the following command. This will get the latest bug fixes and security updates by updating the software on your EC2 instance:

sudo yum update


Now install the PHP software using following command. This command installs multiple software packages and related dependencies:

sudo amazon-linux-extras install -y lamp-mariadb10.2-php7.2 php7.2


Now we Install Apache web server:

sudo yum install -y httpd


Start the Apache web server using following command:

sudo systemctl start httpd


Configure the web server to start with each system boot using following command:

sudo systemctl enable httpd
