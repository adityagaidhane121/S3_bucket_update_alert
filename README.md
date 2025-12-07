# S3_bucket_update_alert
In this project I used Lambda, SNS, and S3 services.
Step 1: Created S3 bucket
<img width="1901" height="920" alt="1" src="https://github.com/user-attachments/assets/06a8b8bd-dfbe-4379-8932-a6ea9b394c10" />
<img width="1920" height="933" alt="2" src="https://github.com/user-attachments/assets/6bcfbb05-97b6-4a6a-899f-17c4e966cf20" />
Step 2: Created lambda function.
<img width="1920" height="911" alt="3" src="https://github.com/user-attachments/assets/7fba84a5-bfba-4f31-8c30-36f2b9960c8d" />
Step 3: I have created a new role from AWS policy templates.
<img width="1920" height="931" alt="4" src="https://github.com/user-attachments/assets/cb42aca1-54cd-4cd8-b559-179a75198a3b" />
Step 4: Then add a trigger pointing to the S3 bucket.
<img width="1920" height="933" alt="5" src="https://github.com/user-attachments/assets/38957bea-9798-4435-83f2-3a6b0ad42b91" />
Step 5: Add destination to SNS topic 'update.'
<img width="1909" height="926" alt="6" src="https://github.com/user-attachments/assets/c0de6ebe-aae8-47fb-b3af-68cdf4ea5d90" />
<img width="1920" height="899" alt="7" src="https://github.com/user-attachments/assets/41767ea9-0b47-4034-aaf3-fe321478365e" />
<img width="1920" height="923" alt="8" src="https://github.com/user-attachments/assets/15d52425-a420-47e0-b741-65324ef8642b" />
<img width="1920" height="937" alt="9" src="https://github.com/user-attachments/assets/d35ff5e5-314d-464b-b704-143d2c3fe48f" />
Results: Whenever we try to upload any object in an S3 bucket, we will get a simple notification service (SNS) alert message on email.
