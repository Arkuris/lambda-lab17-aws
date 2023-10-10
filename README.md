# lambda-lab17-aws

### a description of how to use your lambda.
  - uhhhh... upload an image to the C3 bucket and it will process it through the lambda function to make sure it is either a .png or .jpeg. Then it should implement the data into the images.json file with info about the image.

### a description of any issues you encountered during deployment of this lambda.
  - I ran into issues caused by the server locations changing from my Lambda tab and my S3 tab.
  - I have the S3 bucket and the Lambda linked but I dont know how to test out the function.
  - I uploaded an image to the C3 bucket but im not getting a log on the lambda function.
  - managed to fix the above issues as I worked through the lab.
  - still having a small issue where the images.json file doesnt seem to be updating right away. Maybe its AWS being slow idk... 

### a link to your images.json file.
- [Link to my AWS S3](https://s3.console.aws.amazon.com/s3/buckets/lab17-401-ark?region=us-west-2&tab=objects)
- [Link to images.JSON file](https://s3.us-west-2.amazonaws.com/lab17-401-ark/images.json)
