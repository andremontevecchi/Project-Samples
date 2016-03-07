# My Task Checklist

The My Task Checklist sample code demonstrates how to query for assignments for the current user and to submit status updates (complete/incomplete) using C# CSOM.  It also demonstrates how to authenticate against Project online without directly passing the credentials to the application.

## Scenario
As a team member, I want to be able to see my assignments and  quickly check them off to mark them as complete.


### Using App

1.	Choose the PWA site you want to connect to and click connect.
2.	Authenticate as a team member.
3.	Check and uncheck assignments
5.	Click Submit.


### Prerequisites/Deployment
To use this code sample, you need the following:
* Project Online
* Visual Studio 2013 or later 
* Project CSOM client DLL.  It is available as a Nuget Package from [here](https://www.nuget.org/packages/Microsoft.SharePointOnline.CSOM/)



## How the sample affects your tenant data
This sample runs CSOM methods that read assignment information for the logged in user and will update the percent complete. Tenant data will be affected.

## Additional resources
* [Client-side object model (CSOM) for Project 2013](https://msdn.microsoft.com/en-us/library/office/jj163123.aspx)
* [Project 2013 SDK](https://www.microsoft.com/en-us/download/details.aspx?id=30435)
* [SharePoint Online SDK](https://www.microsoft.com/en-us/download/details.aspx?id=42038)

## Copyright
Copyright (c) 2016 Microsoft. All rights reserved.