# Hosting-a-static-website-using-S3
Step-by-Step Instructions:

1. Create an S3 Bucket

~Log into your AWS account and open the S3 Management Console.

~Click "Create Bucket".

~Choose a unique bucket name (e.g., my-website-bucket).

~Select the region closest to you.

~Uncheck "Block all public access" to make the bucket publicly accessible.

2. Upload Website Files
Open the created bucket and click "Upload".

Drag and drop your static website files (HTML, CSS, JS, etc.)

3. Enable Static Website Hosting

In your S3 bucket, go to the "Properties" tab.

Scroll down to "Static Website Hosting" and click "Edit".

Select "Enable" and choose "Host a static website".

In the "Index document" field, enter your main HTML file (e.g., index.html).

Optionally, specify an error document (e.g., error.html).

Click "Save changes".

4. Access Your Website

Go to the "Properties" tab and scroll to "Static Website Hosting".

You will see the endpoint URL under the "Bucket website endpoint." This is the URL where your static website is hosted.

Open the URL in a browser to see your live static site.

5.Make Public using ACL

click on the index.html file 

actions --> make public using ACL

6.RUN

by using Static website hosting link we can run the webpage

![1](https://github.com/user-attachments/assets/cf9d4811-7eb2-4c24-8db7-122bdf34f909)


![2](https://github.com/user-attachments/assets/6be830b2-47dd-43c1-af8c-e180eff7cc8d)


![Screenshot 2024-10-20 175054](https://github.com/user-attachments/assets/9b680e80-e77a-4438-8a79-d97e7f1af113)


![4](https://github.com/user-attachments/assets/99c4def6-e9d5-45e8-bd72-f03c501a40e5)


![Screenshot 2024-10-20 173814](https://github.com/user-attachments/assets/605007ad-9e4b-41bb-b873-90f3a284b72d)


![Screenshot 2024-10-20 173835](https://github.com/user-attachments/assets/59489e64-9f3f-4efe-b30f-ed88fe69129c)


![Screenshot 2024-10-20 173913](https://github.com/user-attachments/assets/5dce8dae-59c8-4a2e-a2c7-3fc61baaad9d)


![Screenshot 2024-10-20 174030](https://github.com/user-attachments/assets/859cbc9f-3c4b-4d8d-bc5b-98bdc9601b84)


![Screenshot 2024-10-20 174137](https://github.com/user-attachments/assets/6412ff53-1913-496d-9153-301fd7d40e40)


![Screenshot 2024-10-20 174413](https://github.com/user-attachments/assets/ab8a87ce-ac89-418a-8823-7705ff637646)
