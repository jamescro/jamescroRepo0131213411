# Major services and features in Microsoft Graph

Microsoft Graph enables you to integrate with the best of Office 365, Windows 10, and enterprise mobility and security services in Microsoft 365. Additionally, you can leverage social and security intelligence to boost user productivity, creativity, and team collaboration, and to protect business resources and users' data. 

Some services in Microsoft Graph make their debut there, others have been well-known as standalone services and are now converging in Microsoft Graph. Their API sets follow a streamlined design as detailed in the [Microsoft REST API guidelines](https://github.com/Microsoft/api-guidelines), and are now accessible through the single Microsoft Graph REST endpoint `https://graph.microsoft.com`. The major services and features are listed below by category.

<!-- Per M365 enterprise categorization on https://www.microsoft.com/en-us/microsoft-365/enterprise/home

Office applications
Workbooks and charts - Excel
Email and calendar - Outlook
Files - OneDrive
Notes - OneNote

Business applications
(Bookings)

Collaboration services
Microsoft Teams
SharePoint
Planner
(Yammer)

Education
(https://www.microsoft.com/en-us/education/buy-license/microsoft365/default.aspx)
"Empower educators to unlock creativity, promote teamwork, and provide a simple and safe experience in a single, affordable solution built for education."

Identity and access management
AAD
Identity provider
(https://developer.microsoft.com/en-us/graph/docs/api-reference/beta/resources/identityprovider)
Invitation manager (https://developer.microsoft.com/en-us/graph/docs/api-reference/beta/resources/invitation)
Privileged Identity Management(https://developer.microsoft.com/en-us/graph/docs/api-reference/beta/resources/privilegedidentitymanagement_root)(https://docs.microsoft.com/en-us/azure/active-directory/active-directory-privileged-identity-management-configure)

Security
- Intelligent threat detection 
AAD risk detection (https://developer.microsoft.com/en-us/graph/docs/api-reference/beta/resources/identityriskevent)
(https://docs.microsoft.com/en-us/azure/active-directory/active-directory-reporting-risk-events)

Mobile device and app management
(Slides in community call https://www.slideshare.net/OfficeDev/microsoft-graph-community-call-2618)
Application, device, and data security
Protects data whether employees use store apps, web apps, or LOB apps
Protects data whether employees use Windows PC, Android, iOS or OSX devices
... whether data is stored in the cloud, on device or on-premises.
Microsoft Intune

Cross-device experiences
Project Rome

Social intelligence (analytics)
Insights
People API

Office 365 service usage reports
Reports  


-->

## Office productivity

|Feature    |Supporting services  |Description |More information |
|:-----------|:--------------------|:-----------|:----------------|
| Calendar | Outlook  |  |  |
| Files | OneDrive |  |  |
| Mail | Outlook | A messaging communication hub in Office 365 that also lets you manage contacts, schedule meetings, find information about users in an organization, initiate online conversations, share files, and collaborate in groups. | [Outlook mail overview](../concepts/outlook-mail-concept-overview.md) |
| Notes | OneNote | Lets users plan and organize ideas and information. | [OneNote overview](../concepts/integrate_with_onenote.md) |
| Personal contacts | Outlook |  |  |
| Workbooks and charts | Excel |  |  |

## Collaboration

<!-- Want to update links to concept overviews as they are created over time. 
-->
|Feature    |Supporting services  |Description |More information |
|:-----------|:--------------------|:-----------|:----------------|
|Groups | Azure, OneDrive, OneNote, Outlook, Planner | Office 365 groups for users to share conversations, files, notes, calendar, and plans. | [Groups API overview](../api-reference/v1.0/resources/groups-overview.md) |
|Plans and tasks | Planner | Enables Office 365 groups to create plans, assign tasks, and track progress. | [Planner API overview](../api-reference/v1.0/resources/planner_overview.md) |
| Shared site and content  | SharePoint | Web-based platform for users and Office 365 groups to share and manage content (including lists, files, and notes). | [SharePoint API overview](../api-reference/v1.0/resources/sharepoint.md) | 
|Teamwork (preview) |  Microsoft Teams | Chat-based workspace for teams to share files, notes, calendar, and plans. |

## Education


## Enterprise mobility

|Feature    |Supporting services  |Description |More information |
|:-----------|:--------------------|:-----------|:----------------|
|Mobile device management | Intune | Lets organizations provide their employees access to company resources, data, and applications, while helping to protect their corporate information. | [Intune API overview](../api-reference/v1.0/resources/intune_graph_overview.md) |


## Identity service





