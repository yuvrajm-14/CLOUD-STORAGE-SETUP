# CLOUD-STORAGE-SETUP

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: YUVRAJ VISHVANATH MUDLIYAR

**INTERN ID**: CODHC203

**DOMAIN**: CLOUD COMPUTING

**DURATION**: 12 WEEKS

**MENTOR**: NEELA SANTOSH

#DESCRIPTION

STEP 1: Log in to AWS
1.	Go to https://aws.amazon.com/
2.	Click Sign In to the Console.
3.	Log in with your AWS credentials.

   
STEP 2: Go to S3
1.	In the AWS Console, type "S3" in the search bar.
2.	Click on "S3" (Simple Storage Service).


STEP 3: Create a Bucket
1.	Click "Create bucket".
2.	Choose a region closest to you on top right corner
3.	Enter a unique bucket name (e.g., my-first-s3-bucket-username).
4.	Leave the rest of the settings default unless you need:
o	Versioning (for file version control).
o	Encryption (for data-at-rest encryption).
5.	Uncheck "Block all public access" ONLY if you want to allow public access & acknowledge it via clicking the checkbox (e.g., hosting a public file or website).
6.	Click Create bucket at the bottom.

   
STEP 4: Upload Files to the Bucket
1.	Click on your bucket name in the list.
2.	Click "Upload".
3.	Click "Add files" and select example files from your computer.
4.	Click Upload.

   
STEP 5: Set Permissions (Public or Private Access)
Option A: Make Files Public (Use Caution!)
1.	Go to the "Permissions" tab.
2.	Scroll to "Object ownership" and make sure the bucket allows public access (see Step 3, point 5).
3.	Under “Object ownership  " click Edit. -> Select the ACLs enabled -> click on acknowledge
4.	Save changes.
5.	Go to Object Tab
6.	Select the uploaded file.
7.	Click on Actions-> Click on Make Public using ACLs
8.	Click on Make Public
9.	Go to Object tab-> Click on the File name
10.	Now, you'll see a public URL for the file under the "Object URL".

    
Option B: Share Files with Specific Users (IAM or Pre-Signed URL) (Privately)
1.	Go to the file in the bucket.
2.	This will Work Even if Turned on "Block all public access" and “Object Ownership is disabled”
3.	Click "Actions" > "Share with a pre-signed URL" (valid for a limited time).

   
STEP 6: Test the Setup
•	Try accessing the file using the Object URL in your browser.
•	If it's public, it should load directly.
•	If private, test with a pre-signed URL



#OUTPUT
![image](https://github.com/user-attachments/assets/ac01549a-7ee3-41e9-b782-cb4f41bf3c16)



![image](https://github.com/user-attachments/assets/1b6ce0b7-bf30-4961-ac8a-82fd402ebf8d)


![image](https://github.com/user-attachments/assets/0eed6e56-e314-4f64-9619-b9dfb8d7c71c)



![image](https://github.com/user-attachments/assets/f11e34e2-bd57-4c70-b82d-5846f3d261d1)



![image](https://github.com/user-attachments/assets/d9e0990d-0885-42c1-8923-3761d266ec35)


![image](https://github.com/user-attachments/assets/8deba23d-7330-449c-888e-097b050381fd)



![image](https://github.com/user-attachments/assets/8da70d60-c0b1-4823-94be-9815fca7dbd0)



![image](https://github.com/user-attachments/assets/e8291feb-95ea-45aa-a2e5-9e8ac2db1879)



![image](https://github.com/user-attachments/assets/48329ca2-732e-4466-96e5-b457b7335e6d)

