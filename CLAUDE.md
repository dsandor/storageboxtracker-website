This is a marketing website for my StorageBoxTracker.com mobile app. This app allows you to track your storage boxes and their contents. the big feature is that the app supports NFC so a user can tap the phone on the nfc sticker on the box and the app will pop up the contents of the box. users can also search for boxes and tag a box in the app with labels. the app will automatically generate tags for the box based on pictures. users can print labels to a standard inkjet printer or to a Dymo Labelwriter usb printer. Attached are some marketing photos used in the app store.

Deployment should occur to AWS. 
AWS Credentials will be set up as needed.

Directory Structure

./website - stores all the web html code
./aws - SAM/CloudFormation template used to create AWS infrstructure such as CloudFront, S3, Etc. to serve the web application.

Github is the SCM repo. AWS Credentials will exist in environment variables in github so actions can run.

