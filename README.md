# All Things 365 MSM Showcase PowerApp and SharePoint_Library_MSN Power Automate flow
Surfaces rich Media Service Metadata for SharePoint Library repositories.

Import this solution into your Power Apps environment.


Before uploading this Power App into your environment you will need to ensure the user uploading the package via the "Import canvas app" link in the Power Apps web studio has a Power Apps Plan 2 license or Trial license assigned to that user. 

If not, when importing the app you will likely receive an error message indicating the 2 flows associated to the app were not imported, with a rather obsure error message which (if you can find) will inform you that user does not have a license plan necessary to import the app. 

Per a thread on the Power Apps community site you can obtain a 90 day trial license in order to test and evaluate this app in your Power Apps environment per the following links for additional insight (and to sign up for the trial license):
https://powerusers.microsoft.com/t5/Building-Power-Apps/What-is-quot-Microsoft-PowerApps-Trial-Plan-2-quot/m-p/131622#M45812
https://powerapps.microsoft.com/en-us/#


This solution showcases how you are able extract some awesome metadata that is automatically generated for most types of files uploaded to most types of SharePoint libraries. 

Metadata is typically generated for files uploaded to SharePoint on average about 4 hours after the file was uploaded. Don't be too concerned that the app isn't working as you might expect having immediately uploaded files to any given library. Equally metadata won't get extracted from PDF documents based on the limited testing done prior to sharing this solution.

The Power App requires you to add 4 datasources connections to 4 SharePoint libraries on a team site:
The standard "Shared Documents" / "Documents" Library
The standard "Site Assets" / "SiteAssets" Library
A new app - "Picture Library" named "Pictures"
A new app - "Media Library" named "Media Assets"

In additional to the 4 Libraries, test the corresponding Power Automate flow provisioned in this package "SharePoint_Library_MSM" prior to running the app.

Part 1
https://masteroffice365.com/media-service-metadata-part-1
https://youtu.be/4dhDk36GVJU
Power App showcase surfacing rich metadata leveraging the SharePoint RenderListDataAsStream REST API
https://youtu.be/8QbY9q-Sl0c
Power Automate flow that exposes rich metadata leveraging the SharePoint RenderListDataAsStream API

...................................................................................................................
Part 2
https://youtu.be/GY5RGAAm84s
Power App showcase surfacing rich metadata levaging the SharePoint Graph v2 REST APIs

...................................................................................................................

Stay tuned for more...

https://www.youtube.com/watch?v=gKL92VU6QwA
