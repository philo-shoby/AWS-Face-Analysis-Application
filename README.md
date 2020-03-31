# aws-face-recognition-project

This project is made using AWS services and Telegram.

-The Telegram Bot is used to as API in which the photo is uploaded. This photo is send to EC2 service.

-The EC2 will upload this photo in S3 service and invokes Amazon Rekognition service.

-The S3 service will send this photo to Rekognition service and it identify the total number of faces.

-The result is send to EC2.

screenshots.docx contains the step by step procedure.
