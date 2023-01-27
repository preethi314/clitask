# clitask
-linux-2/
[ec2-user@ip-172-31-3-253 ~]$ touch a.txt
[ec2-user@ip-172-31-3-253 ~]$ touch b.txt
[ec2-user@ip-172-31-3-253 ~]$ vi dummy.yml
[ec2-user@ip-172-31-3-253 ~]$ vi dummy1.yml
[ec2-user@ip-172-31-3-253 ~]$ vi dummy2.yml
[ec2-user@ip-172-31-3-253 ~]$ ls
a.txt  b.txt  dummy1.yml  dummy2.yml  dummy.yml
[ec2-user@ip-172-31-3-253 ~]$ aws configure
AWS Access Key ID [None]: AKIAYQFXSBMYC2D674US
AWS Secret Access Key [None]: 37RjpJnx8Fyn/BZlVDldjldq6SXQxg681cuV04Zk
Default region name [None]: us-east-1
Default output format [None]: json
[ec2-user@ip-172-31-3-253 ~]$ aws s3 cp a.txt s3://preethi-guvi-task/
upload: ./a.txt to s3://preethi-guvi-task/a.txt
[ec2-user@ip-172-31-3-253 ~]$ aws s3 cp b.txt s3://preethi-guvi-task/
upload: ./b.txt to s3://preethi-guvi-task/b.txt
[ec2-user@ip-172-31-3-253 ~]$ aws s3 cp dummy1.yml s3://preethi-guvi-task/
upload: ./dummy1.yml to s3://preethi-guvi-task/dummy1.yml
[ec2-user@ip-172-31-3-253 ~]$ aws s3 cp dummy.yml s3://preethi-guvi-task/
upload: ./dummy.yml to s3://preethi-guvi-task/dummy.yml
[ec2-user@ip-172-31-3-253 ~]$ aws s3 cp dummy2.yml s3://preethi-guvi-task/
upload: ./dummy2.yml to s3://preethi-guvi-task/dummy2.yml
