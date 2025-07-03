
Deploy AWS Three-Tier Web in a Single AZ

![image](https://github.com/user-attachments/assets/a642658b-c36d-4f8a-b09f-d1712d8cdf6f)


Development VPC.

![image](https://github.com/user-attachments/assets/0a165127-a449-4ee8-8075-5dba32e23a13)



Installing an EC2 instance in a public and private subnet using Amazon Linux .
 ![image](https://github.com/user-attachments/assets/c92b9c04-26a7-4a31-b1bd-6fd71676bf88)

 
The DevWebTier was deployed in a public subnet, allowing for public internet access for users.



The security group for the Development

![image](https://github.com/user-attachments/assets/093bd32d-5d04-410d-bfe1-b4998f79d3ef)


Dev-dbserver and DevAppLayer are placed in the private subnet with no public IP.	
![image](https://github.com/user-attachments/assets/b7d02bdc-40bd-4f85-b48c-0efad4e1723f)


 
The security group for the dev-dbserver only allows incoming connections from the devApplayer security group, not from the public internet.
![image](https://github.com/user-attachments/assets/da5fa6ed-a54d-46e0-a941-71d91a22c940)


 
Deployed the Database Layer
 

 ![image](https://github.com/user-attachments/assets/81929dd2-efa7-4a1a-b1a9-87500c769018)


![image](https://github.com/user-attachments/assets/fc6ae23e-f623-4c7a-b80f-c555dfdcd7f0)

 ![image](https://github.com/user-attachments/assets/941097f6-26ca-484d-ab7a-51e6eb16a216)

Create a DB subnet group
 
 
![image](https://github.com/user-attachments/assets/f3fb1f80-22a9-4c2a-a9b5-3f4edfc8beae)

  
 

 ![image](https://github.com/user-attachments/assets/e7cff5f1-fb72-4a60-8192-4ba3deaad886)

 


  ![image](https://github.com/user-attachments/assets/9dda21c8-74d8-4aec-bfb9-e1f694f9c744)

![image](https://github.com/user-attachments/assets/0b1efef6-207b-4cc5-b1cb-e29ecc5a9920)

 ![image](https://github.com/user-attachments/assets/7bc9786e-8e6a-4c67-a079-6ca16c81c85d)



Login to Applayer.

![image](https://github.com/user-attachments/assets/75ca5253-9ba8-4a5a-963b-84df1d85dc92)

![image](https://github.com/user-attachments/assets/8271192a-e311-4452-a1f8-5e43b426c807)

Installed the mMySQL client and able to login to sever

  
 ![image](https://github.com/user-attachments/assets/fca8e819-3d58-4c8b-a041-d35f925d991c)


 ![image](https://github.com/user-attachments/assets/7d59003f-951f-4472-8cf4-009b796d8446)

 

 
![image](https://github.com/user-attachments/assets/a0d21e9a-cf5a-4156-b08a-1147f41842be)

 
![image](https://github.com/user-attachments/assets/54ea0b21-b449-4e3e-bb76-8ee85eca1d1b)

 ![image](https://github.com/user-attachments/assets/9a114bde-aa5a-4e13-967f-47a1bff8a6f8)

 ![image](https://github.com/user-attachments/assets/8fce7022-25de-490a-b9e6-3504ce110ec3)

![image](https://github.com/user-attachments/assets/4c062fb6-ba09-47e2-a669-f5901daef565)

AppTier
 ![image](https://github.com/user-attachments/assets/e52b222a-0d80-4b6a-b4ba-8233768f1e7a)

 

 ![image](https://github.com/user-attachments/assets/771d256f-47f0-4683-bb4b-a8f3836b5e10)


   
![image](https://github.com/user-attachments/assets/35fd85fe-e50f-4175-b4e1-214e2a227f31)

 ![image](https://github.com/user-attachments/assets/7ba92053-c427-4245-ad83-f2fa9d3522ad)

![image](https://github.com/user-attachments/assets/14a19ddc-6de1-40a2-b4fd-b5914b56c099)

Test App Tier
 ![image](https://github.com/user-attachments/assets/391e3f90-9c62-441d-9f1a-7d663f8c76aa)


Web Tier Instance Deployment
![image](https://github.com/user-attachments/assets/a72336d7-7739-4fef-a12f-92e20812cf40)

 
Able to SSH into the webtier private from the MGMT vpc.
 
 ![image](https://github.com/user-attachments/assets/17bc3e3d-58bb-4cfa-81d1-07a433726b4d)


 ![image](https://github.com/user-attachments/assets/e6e18be5-407b-41f6-b661-5948ae3374ad)


![image](https://github.com/user-attachments/assets/9418384e-5fcf-4a03-af5b-8c7d80699d99)

![image](https://github.com/user-attachments/assets/59c45cfd-bb3b-476c-870e-02f118f677d9)

 ![image](https://github.com/user-attachments/assets/4bd410f4-00d5-4a0d-89f6-c0d4840ea20e)



