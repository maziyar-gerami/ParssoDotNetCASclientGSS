ASP.Net client using GSS package Overview
This a simple sample to use PARSSO CAS with a  dotNet client
Prerequisites

Enabled IIS
Microsoft visual studio 2015 or upper version
after open this project on the IDE, install this package using nuget package manger:
GSS.Authentication.CAS.AspNetCore

Configuration 
In this project, all of the settings, set to work with PARSSO CAS. if your server is different, please change these tages in appsettings.json file:

Deploy
If you open this project with its *.sln fie, you can see its configuration for deploy is > IIS; else you deploy it with an IIS EXPRESS configuration.
