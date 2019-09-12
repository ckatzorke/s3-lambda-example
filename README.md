# s3-lambda-example

Source and details for the S3-Lambda tutorial, that creates a thumbnail, triggered by an upload.  
See also https://docs.aws.amazon.com/en_pv/lambda/latest/dg/with-s3-example.html.

## Install AWS cli

You need python 2.6 or higher (I used python 3.7).

```shell
pip3 install aws-cli
```

## Source code

The source for the function is located in `index.js`.  

## Build the functions package

Run `npm run build`.
