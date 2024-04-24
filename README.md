# Rega-Notification

```
JSON
{
    "Title":"Resa Pipeline Modern Pipeline Run Fail",
    "Message":"The Full Migration Pipeline Failed",
    "Color":"RED",
    "DataFactoryName":"@{pipeline().DataFactory}",
    "PipelineName":"@{pipeline().Pipeline}",
    "PipelineRunID":"@{pipeline().RunId}",
    "Time":"@{formatDateTime(addHours(utcNow(),1),'yyyy-MM-dd')}"
}
```
