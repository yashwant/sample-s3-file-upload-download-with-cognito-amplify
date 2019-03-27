##Deploy to S3

###Build

```
$ npm run build
```

###Upload to S3

```
$ aws s3 sync build/ s3://YOUR_S3_DEPLOY_BUCKET_NAME
```

###Access
Make sure that you have selected  "Use this bucket to host a website" option while creating bucket

```
http://<your bucket name>.s3-website-<region>.amazonaws.com/
```

