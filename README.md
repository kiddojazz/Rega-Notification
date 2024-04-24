# Rega-Notification

```json
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

```html
<hr/>
<h2 style='color:____color_add____'>____title_here____</h2>
<hr/>
Data Factory Name: <b>____name_add____</b><br/>
Pipeline Name: <b>____name_add____</b><br/>
Pipeline Run Id: <b>____id_add____</b><br/>
Time: <b>____time_add____</b><br/>
<hr/>
Information<br/>
<p style='color:____color_add____'>____message_add____</p>
<hr/>
<p style='color:__color_add__;'>This email is auto generated to get more information contact resagratia.com.com</p>
```
