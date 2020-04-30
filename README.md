# RenderListDataAsStream_Library_Metadata
Surfaces rich Media Service Metadata for SharePoint Library repositories
https://masteroffice365.com

This solution showcases how you are able extract some awesome metadata that is automatically generated for most types of files uploaded to most types of SharePoint libraries. 

Metadata is typically generated for files uploaded to SharePoint on average about 4 hours after the file was uploaded. Don't be too concerned that the app isn't working as you might expect having immediately uploaded files to any given library. Equally metadata won't get extracted from PDF documents based on the limited testing done prior to sharing this solution.

The Power App requires you to add 4 datasources connections to 4 SharePoint libraries on a team site:
The standard "Shared Documents" / "Documents" Library
The standard "Site Assets" / "SiteAssets" Library
A new app - "Picture Library" named "Pictures"
A new app - "Media Library" named "Media Assets"

In additional to the 4 Libraries, add the corrosponding Flow provisioned in this package "SharePoint_Library_MSM" which you MUST test prior to running the app.
