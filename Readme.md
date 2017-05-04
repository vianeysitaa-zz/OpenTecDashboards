## Power BI Embedded ##

>This repository contains a sample Web App with a Power BI Embedded report.
>In order to use it with your own reports, you need to modify Web.config, and put the data from your Power BI Embedded Report in Azure. 
>You need the Access Key, the Workspace Collection Name and the Workspace Id.
```xml
 <appSettings file="Cloud.config">
    <add key="powerbi:AccessKey" value="" />
    <add key="powerbi:WorkspaceCollection" value="" />
    <add key="powerbi:WorkspaceId" value="" />
  </appSettings>
```
