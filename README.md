# demo_express_AWS_S3_app
A simple demo Express app for uploading /retrieving files with Amazon S3 

* If you haven't set up your AWS S3 bucket yet , then setting up your s3 bucket and getting your access key pairs will be the first thing to do.If you need instructions on this topic,you can take a look at my medium post-https://medium.com/@anikislam/setting-up-aws-s3-bucket-and-uploading-and-getting-files-using-express-js-part-1-ebbc1bcabb2b

* Clone this repository-
  - git clone https://github.com/rabiulislamanik/demo_express_AWS_S3_app.git

* Run this command - 'npm install'.

* Edit the keys.js file-
  - Replace in Line 2, ‘XXXXXXXXXXXXXXXXXXXX’ with the Access Key ID.
  
  - Replace in Line 2, ‘XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX’ with the Secret Access Key ID.
  
* Edit the server.js file-
  - Replace in Line 24, 'sample-region' with the region of your target bucket.Check your bucket region name from here-  https://docs.aws.amazon.com/general/latest/gr/rande.html .
  
  - Replace in Line 53, ‘sample-bucket-name’ with your target bucket's name.
  
  - Replace in Line 79, ‘sample-bucket-name’ with your target bucket's name.

* Run this command - 'npm run server'.

#### If you want to get the URLs of the files ,then you can add the code in this gist-

<script src="https://gist.github.com/rabiulislamanik/f488c6c500d807b9704f7612e0a7acfd.js"></script>