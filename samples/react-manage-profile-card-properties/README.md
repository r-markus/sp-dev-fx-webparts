# Manage Profile Card Properties 

## Summary

This web part allows tenant administrators to manage profile card properties.  
We can create, edit, delete, directory properties that can be add to profile card.

Only users with Tenant Admin Role are allowed to managed profile card properties. 

## Manage Profile Card Properties

![manageProps](assets/Screenshot1.png)

![manageProps](assets/Screenshot2.png)

![manageProps](assets/Screenshot3.png)

![manageProps](assets/Screenshot4.png)

![manageProps](assets/Screenshot5.png)


## Compatibility

![SPFx 1.11](https://img.shields.io/badge/SPFx-1.11.0-green.svg)
![Node.js v10](https://img.shields.io/badge/Node.js-v10-green.svg)
![Compatible with SharePoint Online](https://img.shields.io/badge/SharePoint%20Online-Compatible-green.svg)
![Does not work with SharePoint 2019](https://img.shields.io/badge/SharePoint%20Server%202019-Incompatible-red.svg "SharePoint Server 2019 requires SPFx 1.4.1 or lower")
![Does not work with SharePoint 2016 (Feature Pack 2)](https://img.shields.io/badge/SharePoint%20Server%202016%20(Feature%20Pack%202)-Incompatible-red.svg "SharePoint Server 2016 Feature Pack 2 requires SPFx 1.1")
![Teams Incompatible](https://img.shields.io/badge/Teams-Incompatible-lightgrey.svg)
![Local Workbench Incompatible](https://img.shields.io/badge/Local%20Workbench-Incompatible-red.svg "This solution requires access to Microsoft Graph API")
![Hosted Workbench Compatible](https://img.shields.io/badge/Hosted%20Workbench-Compatible-green.svg)

## Applies to

* [SharePoint Framework](https://docs.microsoft.com/sharepoint/dev/spfx/sharepoint-framework-overview)
* [Office 365 tenant](https://docs.microsoft.com/sharepoint/dev/spfx/set-up-your-development-environment)

## Web Part Properties
 
Property |Type|Required| comments
--------------------|----|--------|----------
WebPart Title| Text| no|
 

## Solution

The Web Part Use Microsoft Graph API, Fluent-UI components.

Solution|Author(s)
--------|---------
Manage Profile Card Properties |João Mendes

## Version history

Version|Date|Comments
-------|----|--------
1.0.0|July 28, 2020|Initial release
1.0.1|October 5, 2020|Initial release

## Minimal Path to Awesome

- Clone this repository
- Move to sample folder
- In the command line run:
  - `npm install`
  - `gulp build`
  - `gulp bundle --ship`
  - `gulp package-solution --ship`
  - Add to AppCatalog and deploy
- Approve the required permissions (`User.ReadWrite`, `Directory.AccessAsUser.All`) on SharePoint Admin in App permissions

> **NOTE:** This web part does not work in the local workbench


## Help

We do not support samples, but we this community is always willing to help, and we want to improve these samples. We use GitHub to track issues, which makes it easy for  community members to volunteer their time and help resolve issues.

If you're having issues building the solution, please run [spfx doctor](https://pnp.github.io/cli-microsoft365/cmd/spfx/spfx-doctor/) from within the solution folder to diagnose incompatibility issues with your environment.

If you encounter any issues while using this sample, [create a new issue](https://github.com/pnp/sp-dev-fx-webparts/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Abug-suspected%2Csample%3A%20react-manage-profile-card-properties&template=bug-report.yml&sample=react-manage-profile-card-properties&authors=@joaojmendes&title=react-manage-profile-card-properties%20-%20).

For questions regarding this sample, [create a new question](https://github.com/pnp/sp-dev-fx-webparts/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Aquestion%2Csample%3A%20react-manage-profile-card-properties&template=question.yml&sample=react-manage-profile-card-properties&authors=@joaojmendes&title=react-manage-profile-card-properties%20-%20).

Finally, if you have an idea for improvement, [make a suggestion](https://github.com/pnp/sp-dev-fx-webparts/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Aenhancement%2Csample%3A%20react-manage-profile-card-properties&template=question.yml&sample=react-manage-profile-card-properties&authors=@joaojmendes&title=react-manage-profile-card-properties%20-%20).

## Disclaimer

**THIS CODE IS PROVIDED *AS IS* WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**


<img src="https://pnptelemetry.azurewebsites.net/sp-dev-fx-webparts/samples/react-manage-profile-card-properties" />
