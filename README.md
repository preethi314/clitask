# clitask
-linux-2/  
 touch a.txt  
 touch b.txt  
 vi dummy.yml  
vi dummy1.yml  
 vi dummy2.yml    
 ls  
a.txt  b.txt  dummy1.yml  dummy2.yml  dummy.yml  
 aws configure  
AWS Access Key ID [None]: AKIAYQFXSBMYC2D674US  
AWS Secret Access Key [None]: 37RjpJnx8Fyn/BZlVDldjldq6SXQxg681cuV04Zk  
Default region name [None]: us-east-1  
Default output format [None]: json  
 aws s3 cp a.txt s3://preethi-guvi-task/  
upload: ./a.txt to s3://preethi-guvi-task/a.txt  
 aws s3 cp b.txt s3://preethi-guvi-task/  
upload: ./b.txt to s3://preethi-guvi-task/b.txt  
 aws s3 cp dummy1.yml s3://preethi-guvi-task/  
upload: ./dummy1.yml to s3://preethi-guvi-task/dummy1.yml  
 aws s3 cp dummy.yml s3://preethi-guvi-task/  
upload: ./dummy.yml to s3://preethi-guvi-task/dummy.yml  
 aws s3 cp dummy2.yml s3://preethi-guvi-task/  
upload: ./dummy2.yml to s3://preethi-guvi-task/dummy2.yml  


![Screenshot (260)](https://user-images.githubusercontent.com/116999513/215096716-4fda059c-0401-48b0-a007-68f43d12787a.png)
![Screenshot (261)](https://user-images.githubusercontent.com/116999513/215096724-1ad927a4-2420-4bc4-8628-d9675a0f9fd1.png)
![Screenshot (263)](https://user-images.githubusercontent.com/116999513/215096735-c4c8c220-ae95-41a7-9573-718d96eb0bfc.png)
![Screenshot (264)](https://user-images.githubusercontent.com/116999513/215096742-b2b99503-9c1f-4711-becd-e307550ab4b0.png)
