# kwikpic_inter_ques

to upload to s3 bucket :

import boto3

client = boto3.client('s3')

client.upload_file('images/image_123.jpg', 'mybucket', 'image_123.jpg')
