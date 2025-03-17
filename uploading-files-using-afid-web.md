---
title: Uploading Files Using AFID Web
description: Uploading Files Using AFID Web
---

# Uploading Files Using AFID Web

This guide will walk you through the process of uploading files to AFID using AFID Web.

## Prerequisites

Before you begin, ensure that you have logged in to AFID Cloud and have access to the desired bucket.
Also, ensure that you have the necessary permissions to upload files to the desired bucket. Then create a new bucket in the dashboard with the proper access keys and secret keys. In case of AWS S3, make sure that both 'GetObject' and 'PutObject' permissions are enabled for the bucket.


## Uploading Files

To upload files to AFID, follow these steps:

1. Open the AFID Web application.
2. If you are adding the bucket for the first time, click on the 'Create Bucket' button. Follow this [guide](https://tknsunil.github.io/user-guides/Working%20With%20New%20S3%20UI.html#form-page) to create a new bucket.
3. Once the bucket is created, select the bucket from the list of buckets.
  ![image](https://github.com/user-attachments/assets/8e5113e8-21af-418f-82c6-44203d5a6d39)
4. For each bucket video files must be uploaded to a folder/collection. If there are no folders/collections, create one. 
  ![image](https://github.com/user-attachments/assets/cfdca9e2-0d06-48c1-9fa7-aa88d1446a9d)
  ![image](https://github.com/user-attachments/assets/2496f19a-5b67-4485-9efa-aab05179b9d1)


5. Select the folder/collection from the list of file tree on the left side of the screen.
  ![image](https://github.com/user-attachments/assets/3b9c5b35-e5b9-497f-a7d7-991c68b8d446)
  ![image](https://github.com/user-attachments/assets/36786175-eb58-46b2-ba7d-58b18a0517b5)

6. Click on the 'Upload' Icon button or drag and drop the files to the drop zone.
![image](https://github.com/user-attachments/assets/b6272e7f-6082-423d-a42e-630ead186d0b)

7. Once the files are selected it should start uploading. You can check the progress of the upload in the toast section. Do not close the browser window until the upload is complete.
8. Once the upload is complete, you can view the uploaded files in the file tree. Also the status of the uploaded files will be updated in the file tree.
  ![image](https://github.com/user-attachments/assets/f5cc547b-8e08-43bf-b06f-04138dd82db0)


## Deleting Files

To delete files from the bucket using AFID web, follow these steps: (Note: Deletion permission is required to be assiciated with the bucket keys)

1. Open the AFID Web application.
2. Select the bucket from the list of buckets.
3. Select the folder/collection from the list of file tree on the left side of the screen.
4. Now the files are listed in the file explorer. Click on the 'Delete' button next to the file you want to delete.
  ![image](https://github.com/user-attachments/assets/13c02db7-7c9f-4590-91de-9fdfeb693343)

5. A confirmation box will appear asking you to confirm the deletion.
  ![image](https://github.com/user-attachments/assets/84d72b0c-eebc-4b00-9326-3d988d9bf288)

6. Click on the 'Delete' button to confirm the deletion.
7. **Important!**: This will delete the file from the bucket as well as the AFID dashboard and cannot be recovered from AFID System. So, make sure the backup is setup before deleting.  
  ![image](https://github.com/user-attachments/assets/3b0dfa93-5166-4b01-b300-153732cfc3b2)

