 yum -y update
 yum install httpd -y
 systemctl start httpd
 systemctl enable httpd
 systemctl status httpd
 (If firewall-cmd is failed then install the following)
 sudo yum install firewalld
 sudo systemctl start firewalld
 sudo systemctl enable firewalld
 sudo systemctl status firewalld
 firewall-cmd --zone=public --permanent --add-service=http 
 firewall-cmd --zone=public --permanent --add-service=https
 firewall-cmd --reload

In security group enable 443 port and 80 port http,https
