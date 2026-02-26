# S3 Static Website Hosting Project

This project shows how to host a static website using AWS S3.

---


## Step 1: Create S3 Bucket  
Click Create bucket.

Fill in the details:

Bucket name: Give a unique name (e.g., my-static-website-123).

Region: Choose the region closest to your users (e.g., Asia Pacific (Mumbai)).

Block Public Access Settings:

Click Uncheck “Block all public access” (because static websites need public access).

AWS will warn you—click Acknowledged.

Click Create bucket at the bottom.
![Create Bucket](https://github.com/SAKSHISURYAWANSHI04/s3-static-website-hosting/blob/b8952ee0a98f00b97b7b701cec6b36ae479330d0/imagesstep1.png.png)

---

## Step 2: Upload index.html  
In the S3 console, click on your bucket name

Click Upload → then Add files or Add folder.

Select all your HTML, CSS, JS, images files or the folder containing them.

Click Upload at the bottom.

Wait until the upload finishes.
![Upload File](https://github.com/SAKSHISURYAWANSHI04/s3-static-website-hosting/blob/b8952ee0a98f00b97b7b701cec6b36ae479330d0/imagesstep2.png.png)

---

## Step 3: Enable Static Website Hosting 
Go to Properties tab of your bucket.

Scroll to Static website hosting → click Edit.

Select Enable.

Enter:

Index document: index.html

Error document: error.html (optional)

Click Save changes. 
![Enable Hosting](https://github.com/SAKSHISURYAWANSHI04/s3-static-website-hosting/blob/b8952ee0a98f00b97b7b701cec6b36ae479330d0/imagesstep3.png.png)

---

## Step 4: Add Bucket Policy  
Open your S3 bucket in the AWS console.

Click on the Permissions tab.

Scroll down to Bucket policy → click Edit.

Click Save changes.

Now your bucket allows public read access to all objects → anyone can access your website.
![Bucket Policy](https://github.com/SAKSHISURYAWANSHI04/s3-static-website-hosting/blob/b8952ee0a98f00b97b7b701cec6b36ae479330d0/imagesstep4.png%20(2).png)

---

## Step 5: Open Website URL 
After enabling static hosting, you will see a Bucket website endpoint link.
Open this link in your browser → Your website is now live!  
![Website Output](https://github.com/SAKSHISURYAWANSHI04/s3-static-website-hosting/blob/b8952ee0a98f00b97b7b701cec6b36ae479330d0/imagesstep5.png.png)

---

## Result  
Website is successfully hosted using AWS S3.

