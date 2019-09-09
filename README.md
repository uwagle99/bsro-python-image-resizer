This is a README for Python image resizer


 IMAGE RESIZER PYTHON 2.7
 
(a) Create a directory called CreateThumbnail and put the CreateThumbnail.py file in it
 
(b) use the command "pip install Pillow -t CreateThumbnail" so pip would install the Pillow library directly into that directory (you don't need the boto3 library as new_sel_auto_2019-09-02-18-10-36-820@icrossing.com" 
Lambda already have it)

(c) "cd CreateThumbnail && zip -r9 CreateThumbnail.zip ." - which means, change into the new directory and zip all files and folders recursively.

(d) Update the function using the AWS CLI - "aws lambda update-function-code --function-name CreateThumbnail --zip-file fileb://CreateThumbnail.zip"

(e) Make sure your running environment is actually Python2.7

Run your test again. Make sure you change the arn for the bucket to reflect your bucketName so the output is placed in the correct place. It should work.

