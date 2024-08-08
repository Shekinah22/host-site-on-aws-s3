# Hosting a Static Site on AWS Using S3


## Steps taken to have the code ready for the site


 +  Cloned a public available code for my site
  
  +  Created  a directory for my repository

     <https://github.com/sami-dev/aws-s3-static-website-sample.git>

  +  cd in my created directory
  
  +  cp -r ../aws-s3-static-website-sample/Website/* .

  +  Created a repo at my github in the same sames of my local directory


+  **Ran the following commands on my computer**:

     +  git init
       
     +  git remote add origin https://github.com/Shekinah22/host-site-on-aws-s3.git

     +  git remote -v

     +  git add .

     +  git commit -m "website files"

     +  git push  -n origin main      





+  **Steps taken to do it on aws side**:
  
     +  You need to have a valid aws account
  
     +  You need permission to creat the s3 bucket
  
     +  Create the s3 bucket with an available name of your choice
  
     +  For the site to be publicly accessed, make the permission public

     +  Upload the folders and files from wherever you saved them.  


