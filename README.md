Telerik.Sitefinity.Samples.NewsRotator
======================================

[![Build Status](http://sdk-jenkins-ci.cloudapp.net/buildStatus/icon?job=Telerik.Sitefinity.Samples.NewsRotator.CI)](http://sdk-jenkins-ci.cloudapp.net/job/Telerik.Sitefinity.Samples.NewsRotator.CI/)

The NewsRotator sample project contains a simple Sitefinity widget that rotates news and images present in the Sitefinity backend. The sample features a custom designer that allows you to change the front-end rendering of the widget by switching its template. The NewsRotator widget is built on top of RadRotator widget, part of RadControls for ASP.NET Ajax delivered with this toolkit.

You can run the sample with any type of license. 

Using the NewsRotator sample, you can:

* Create a NewRotator widget
* Register the widget in Sitefinity toolbox
* Create a custom designer to change the widget's template at runtime


### Requirements

* Sitefinity license
* .NET Framework 4
* Visual Studio 2012
* Microsoft SQL Server 2008R2 or later versions

### Prerequisites

Clear the NuGet cache files. To do this:

1. In Windows Explorer, open the **%localappdata%\NuGet\Cache** folder.
2. Select all files and delete them.


### Installation instructions: SDK Samples from GitHub


1. In Solution Explorer, navigate to _SitefinityWebApp_ » *App_Data* » _Sitefinity_ » _Configuration_ and select the **StartupConfig.config** file. 
2. Modify the **dbType**, **sqlInstance** and **dbName** values to match your server settings.
3. Build the solution.

For version-specific details about the required Sitefinity NuGet packages for this sample application, see [Releases](https://github.com/Sitefinity-SDK/Telerik.Sitefinity.Samples.NewsRotator/releases).


### Login

To login to Sitefinity backend, use the following credentials: 

**Username:** admin  
**Password:** password

### Additional resources
Sitefinity documentation
* [Development: Use and extend Sitefinity functionality](http://docs.sitefinity.com/develop-create-and-manage-website-content)
* [NewsRotator widget: Create the NewsRotator as a custom widget](http://docs.sitefinity.com/newsrotator-widget-create-the-newsrotator-as-a-custom-widget)
* [NewsRotator widget: Create the NewsRotator as a user widget](http://docs.sitefinity.com/newsrotator-widget-create-the-newsrotator-as-a-user-widget)
