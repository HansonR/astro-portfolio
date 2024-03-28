## run dev
npm run dev

## update to s3
aws s3 cp dist/ s3://<BUCKET_NAME>/ --recursive
