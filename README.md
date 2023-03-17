This Python project utilizes boto3 to manipulate S3 buckets (an AWS service).
Basically it:
- Creates 2 buckets using a client and a resource
- Creates random files and uploading them to the buckets
- Copies files between the two buckets
- Downloads files from the buckets
- Deletes files from the buckets
- Changes the access list to those files so some are public and some are private
- Encrypts files anfter uploading them
- Enables versioning in the bucket and showing the difference
  between a versioned bucket and and uversioned one
- Prints available bucket names and their stored files
- Deleting buckets

For this code to work we will need:
- Python 3 (I used 3.9)
- An AWS account
- A working & logged in AWS cli
- Installing all of the libs in the requiremets.txt file
