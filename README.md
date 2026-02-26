# S3 Static Website Hosting Project



---


## Step 1: Create S3 Bucket  
1.Click Create bucket.

2.Fill in the details:

3.Bucket name: Give a unique name (e.g.,        my-static-website-123).

4.Region: Choose the region closest to your users (e.g., Asia Pacific (Mumbai)).

5.Block Public Access Settings:

6.Click Uncheck “Block all public access” (because static websites need public access).

7.AWS will warn you—click Acknowledged.

8.Click Create bucket at the bottom.
![Create Bucket](https://github.com/SAKSHISURYAWANSHI04/s3-static-website-hosting/blob/b8952ee0a98f00b97b7b701cec6b36ae479330d0/imagesstep1.png.png)

---

## Step 2: Upload index.html  
1.In the S3 console, click on your bucket name

2.Click Upload → then Add files or Add folder.

3.Select all your HTML, CSS, JS, images files or the folder containing them.

4.Click Upload at the bottom.

5.Wait until the upload finishes.
![Upload File](https://github.com/SAKSHISURYAWANSHI04/s3-static-website-hosting/blob/b8952ee0a98f00b97b7b701cec6b36ae479330d0/imagesstep2.png.png)

---

## Step 3: Enable Static Website Hosting 
1.Go to Properties tab of your bucket.

2.Scroll to Static website hosting → click Edit.

3.Select Enable.

4.Enter:

5.Index document: index.html

6.Error document: error.html (optional)

7.Click Save changes. 
![Enable Hosting](https://github.com/SAKSHISURYAWANSHI04/s3-static-website-hosting/blob/b8952ee0a98f00b97b7b701cec6b36ae479330d0/imagesstep3.png.png)

---

## Step 4: Add Bucket Policy  
1.Open your S3 bucket in the AWS console.

2.Click on the Permissions tab.

3.Scroll down to Bucket policy → click Edit.

4.Click Save changes.

5.Now your bucket allows public read access to all objects → anyone can access your website.
![Bucket Policy](https://github.com/SAKSHISURYAWANSHI04/s3-static-website-hosting/blob/b8952ee0a98f00b97b7b701cec6b36ae479330d0/imagesstep4.png%20(2).png)

---

## Step 5: Open Website URL 
1.After enabling static hosting, you will see a Bucket website endpoint link.

2.Open this link in your browser → Your website is now live!  
![Website Output](https://github.com/SAKSHISURYAWANSHI04/s3-static-website-hosting/blob/b8952ee0a98f00b97b7b701cec6b36ae479330d0/imagesstep5.png.png)

---

## Result  
Website is successfully hosted using AWS S3.

