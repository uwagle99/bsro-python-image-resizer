This is a README for Python image resizer


 IMAGE RESIZER PYTHON ver 2.7
 
 To Create the ZIP for the CreateThumbnail Lambda function and its handler -
 
1) At the root of the project execute - "cd CreateThumbnail && zip -r9 CreateThumbnail.zip ." - which means, change into the new directory and zip all files and folders recursively.

(2) Make sure your running environment is actually Python2.7

 
If you want to make any changes to the Python script then edit the file ///CreateThumbnail/CreateThumbnail.py

Rebuild the ZIp using the above command from the root "cd CreateThumbnail && zip -r9 CreateThumbnail.zip ."
Deploy the generated ZIP to AWS Lambda and test

