# Update the connector in TEST environment

```bash
pac connector update -id 2c57ccdf-d4e9-ee11-a203-002248d8b79c -df independent-publisher-connectors\AmazonS3Bucket\apiDefinition.swagger.json -pf independent-publisher-connectors\AmazonS3Bucket\apiProperties.json -sf independent-publisher-connectors\AmazonS3Bucket\script.csx -sol AWSS3
```

Output:

```log
Connected as michael.megel@mme2k.onmicrosoft.com
Connected to... TEST
Connector updated succesfully.
```

```bash
pac connector create -df independent-publisher-connectors\AmazonS3Bucket\apiDefinition.swagger.json -pf independent-publisher-connectors\AmazonS3Bucket\apiProperties.json -sf independent-publisher-connectors\AmazonS3Bucket\script.csx -sol AWSS3Connector

Connected as a-202500@biontechglobal.onmicrosoft.com
Connected to... [DEV] Michael Megel
Connector created with ID 8d7826fd-1b1f-ef11-840a-002248a27224

pac connector update -id 8d7826fd-1b1f-ef11-840a-002248a27224 -df independent-publisher-connectors\AmazonS3Bucket\apiDefinition.swagger.json -pf independent-publisher-connectors\AmazonS3Bucket\apiProperties.json -sf independent-publisher-connectors\AmazonS3Bucket\script.csx -sol AWSS3Connector
```
