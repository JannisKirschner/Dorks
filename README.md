# Dorks :fire:
Personal Collection of Awesome Google Dorks

## TeamCity
- intext:"TeamCity Professional" and intext:"Build Queue"  
- intitle:"Projects - TeamCity"  

## Confidential Files stored in AWS

- site:"s3-external-1.amazonaws.com" and intext:CONFIDENTIAL
- site:"s3.amazonaws.com" and intext:CONFIDENTIAL
- site:"s3.dualstack.us-east-1.amazonaws.com" and intext:CONFIDENTIAL
  
Just add your target name after the query.  
There are more confidential statuses, for example secret or tlp (traffic light protocol) for military/gov documents.

- site:"s3-external-1.amazonaws.com" and intext:"TOP SECRET"
- site:"s3.amazonaws.com" and intext:"tlp:red"
- site:"s3.amazonaws.com" and intext:"tlp:amber"

## Confidential Files stored in Azure

- site:"blob.core.windows.net" and intext:"CONFIDENTIAL"

## Credentials in Trello

- inurl:trello.com and intext:password
- inurl:trello.com and intext:apikey

## Secrets in Microsoft Devops

- site:"dev.azure.com" and intext:secret
- site:"dev.azure.com" and intext:password
- site:"dev.azure.com" and intext:apikey
