# Grant-Ec2-access-to-S3-SDK

## Steps

### 1) Launche a server with LAMP or LEMP and php8.3-mysql.

![Screenshot (9)](https://github.com/user-attachments/assets/f31e5f4e-f9d8-4f24-bdbc-31e8bd152ed9)

### 2) Created a role and attached it to Ec2.

![Screenshot (26)](https://github.com/user-attachments/assets/47f84b3d-92bd-40e5-9122-1cbf3f7c51f7)
![Screenshot (27)](https://github.com/user-attachments/assets/f6e56c42-bbfa-4448-80a9-c9bc1cb82afe)
![Screenshot (28)](https://github.com/user-attachments/assets/65666744-4bd4-40b6-8c5f-55d64627e8a9)
![Screenshot (29)](https://github.com/user-attachments/assets/49cc74c2-393c-4aa0-bc0f-c46bd74aca5e)
![Screenshot (30)](https://github.com/user-attachments/assets/dc14f47d-0d93-4d00-aaf1-a084d761d449)
![Screenshot (39)](https://github.com/user-attachments/assets/02cd542d-171f-4d4c-a8e7-0e5080712de9)

### 3) Goes in the html folder and make an directory named uploads and give it 777 permissions.

![Screenshot (31)](https://github.com/user-attachments/assets/533ec61f-24fa-4154-a2a0-c9ee79d8a8c6)

### 4) Created a S3 bucket for connecting to the Ec2 for uploaded files directly upload on s3

![Screenshot (33)](https://github.com/user-attachments/assets/e7917ee8-5471-483b-ad60-47c7951e5578)
![Screenshot (34)](https://github.com/user-attachments/assets/026b988c-d86e-4119-ae36-4c921747973d)
![Screenshot (35)](https://github.com/user-attachments/assets/a3e0dcc8-8012-42f7-9d09-a25b7ccd8e12)

### 5) Also created a RDS database for store the links of the photos.

![Screenshot (36)](https://github.com/user-attachments/assets/ae1c786d-8981-4006-ad07-a9b72bbfc27b)
![Screenshot (37)](https://github.com/user-attachments/assets/9ed869a2-8411-41c0-b3ff-4e2b62b82502)
![Screenshot (38)](https://github.com/user-attachments/assets/df926d8a-4c4e-4391-a9e0-285e34f14cab)

### 6) Using RDS endpoint created a database named facebook and table names posts.

![Screenshot (40)](https://github.com/user-attachments/assets/706d9a2b-3fa3-424a-8050-4f87b3f61aa6)

### 7) Created form.html and upload.php and upload the codes in that which is written for the upload ec2 files on S3 and txt data stored in RDS.

![Screenshot (45)](https://github.com/user-attachments/assets/4187d660-0011-46d6-a6c9-9bba99eeaa8a)
![Screenshot (32)](https://github.com/user-attachments/assets/e72829f2-d741-4000-be09-ce5c4aeeb9b7)

### 8) Get ip and see the result on the browser.

## Result:

![Screenshot (41)](https://github.com/user-attachments/assets/0fcefa63-f6e8-4095-b8d9-c3f1f80062dd)
![Screenshot (42)](https://github.com/user-attachments/assets/50c80cc4-eb1b-4e64-bbba-2ba6101e7337)
![Screenshot (43)](https://github.com/user-attachments/assets/8aedd542-8028-4e92-be9a-b089c45dabb8)
![Screenshot (44)](https://github.com/user-attachments/assets/4df045c2-931f-4ce0-b50e-34cbddf9641b)
![Screenshot (46)](https://github.com/user-attachments/assets/ce0ee798-321e-44ed-b7e1-4cc2ace2340d)
  
