# awscommands
Useful AWS commands

View profiles data
```bash
aws configure list
```

Copy and change metadata 
```bash
aws s3 cp s3://my.bucket s3://my.bucket --cache-control max-age=2628000,public --grants read=uri=http://acs.amazonaws.com/groups/global/AllUsers --metadata-directive REPLACE --dryrun
```
(--dryrun is used in order to simulate the copy)
