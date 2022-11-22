## Overview: 
The developer portal is an automatically generated, fully customizable website with the documentation of the APIs within Azure API Management Services. It is where API consumers can discover the APIs.

## Pre-requisites: 
1.	An Active Service Principle with access to Source and Destination Azure API Management Services. 
2.	Existing Source and Destination Azure API Management Services either in same or different subscriptions. 

## Configure the task:
Add the task to the Build / Release pipeline. 

Select the **+ Add tasks** -> **Marketplace** -> **Migrate Azure APIM Developer Portal - Azure API Management**

Add the details as per the table below.

## Extension Overview:
This extension will help in the Migration of Content of the Developer Portal between the Azure API Management Services.

## Task Usage:
| Options                           |	Description                                             |
|-----------------------------------|-----------------------------------------------------------|
| Azure Service Connection          | Should have Access to both the APIMs                      |
| Source APIM Subscription ID       | Subscription ID for Source API Management Services        |
| Source APIM Resource Group        | Resource Group Name for Source API Management Services    |
| Source APIM Name	                | Name for Source API Management Services                   |
| Destination APIM Subscription ID  | Subscription ID for Destination API Management Services   |
| Destination APIM Resource Group	| Resource Group Name for Destination API Management Service|
| Destination APIM Name	            | Name for Destination API Management Services              |

## Notes:
API Management Services can be of Internal, External or None Virtual Network type.
You've to Manually Publish the Developer Portal after the Migration.

## Highlighted feature:
1.	Easy to set up.
2.  One Click Release
3.  Only Azure DevOps Extension for Developer Portal.

## Releases:

### v1.0.0 (November 2022)
* Migrate the content of the Azure APIM Developer portal in same/differet subscriptions.
