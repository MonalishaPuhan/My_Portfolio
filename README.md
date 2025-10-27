⚙️ Deployment Architecture

This portfolio is deployed as a static website using Amazon Simple Storage Service (S3). The S3 bucket is configured as a public website endpoint with the following key features:

 -> Static Website Hosting: Content is served directly from the bucket.
 -> Public Read Access: The Bucket Policy is configured to allow s3:GetObject for the public, ensuring the site is open to all users.
