# awscommands
Useful AWS commands

View profiles data
```bash
aws configure list
```

Copy and change metadata 
```bash
aws s3 cp s3://heek-media/images/ s3://heek-media/images/ --region eu-central-1 --cache-control 'max-age=2628000' --recursive --dryrun
```
(--dryrun is used in order to simulate the copy)
