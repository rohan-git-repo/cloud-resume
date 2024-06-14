# cloud-resume
Deployed site: https://d2tz2jaiu1ret.cloudfront.net/

Go to https://aws.amazon.com

Sign up as root user

Search for S3 and create a new S3 bucket

Upload your files

Search for CloudFront and create a new Distribution

        choose your S3 bucket as your origin domain

        set Origin access OAC as recommended

        create a new OAC policy

        copy OAC policy to your S3 bucket policy

        set viewer protocol policy Redirect to https

        set default root object to your webpage like index.html

        create a new distribution

Wait till the distribution is deployed

Your website is deployed, copy your distribution domain into your browser







