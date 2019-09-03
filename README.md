# Teams-User-Training-Template
Template to create a Microsoft Team in Teams for end users training

This JSON template is intended for companies that have moved to Office 365 and would like to help staff with end-user training.

This template will create a Team, in Microsoft Teams with the following information.
Team Name:		Office 365 User Training
Channel Names:	General, Announcements, Excel, OneDrive, OneNote, Outlook, PowerPoint, Teams, Word, Yammer.

In each channel, there is a tab to Microsoft training resources for that product. The website is loaded inside the tab so users do not need to exit Teams.

To import the JSON file, you will need to use Microsoft Graph Explorer.
https://developer.microsoft.com/en-us/graph/graph-explorer

Login with your admin account to post the JSON file to your Office 365 Tenant. Ensure you have it set to Post - Beta - https://graph.microsoft.com/beta/Teams

![](images/Microsoft%20Graph%20Explorer%20Post.png)

Past the text from the JSON file in to the request body and hit Run Query

Once you it is completed you should see Success - Status Code 202, it will take a few minutes the script to create the Team, channels and tabs.
![](images/Microsoft%20Graph%20Explorer%20Post%20Success.png)

Here is what it should look like.
![](images/Microsoft%20Teams%20Office%20user%20Training.png)
