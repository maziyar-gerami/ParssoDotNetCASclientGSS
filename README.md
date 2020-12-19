**ASP.Net client using GSS package Overview**<br>
This a simple sample to use PARSSO CAS with a  dotNet client<br>

**Prerequisites**<br>
Enabled IIS<br/>
Microsoft visual studio 2015 or upper version <br/>
after open this project on the IDE, install this package using nuget package manger: <br/>
GSS.Authentication.CAS.AspNetCore <br/>

**Configuration** <br>
In this project, all of the settings, set to work with PARSSO CAS. if your server is different, please change this tag in `appsettings.json` file:<br/>
ServerUrlBase

**Deploy**<br>
If you open this project with its `*.sln` fie, you can see its configuration for deploy is > IIS; else you deploy it with an IIS EXPRESS configuration.
