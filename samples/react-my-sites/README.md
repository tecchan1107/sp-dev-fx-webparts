---
page_type: sample
products:
- office-sp
languages:
- javascript
- typescript
extensions:
  contentType: samples
  technologies:
  - SharePoint Framework
  - Microsoft Graph
  platforms:
  - React
  createdDate: 4/9/2020 12:00:00 AM
---

# My Sites

## Summary

This web part shows sites that user has permissions to access. It includes Office 365 Groups, OneDrive Sites, SharePoint Sites and  App Sites created by SharePoint Add-ins.

Each Site has a symbol indicate if it is SharePoint Site, Group, Group and OnDrive.
If the Group has a microsoft team associated and user has permissions to access the symbol of teams will be displayed.
  



![MySites](./assets/MySites.gif)

![MySites](./assets/Screenshot%202020-08-06%20at%2013.50.51.png)

![Birthdays Web Part](./assets/Screenshot%202020-08-06%20at%2013.52.58.png)

![PersonalApps](./assets/Screenshot%202020-08-06%20at%2014.17.35.png)


## Compatibility

![SPFx 1.11](https://img.shields.io/badge/SPFx-1.11.0-green.svg)
![Node.js LTS 10.x](https://img.shields.io/badge/Node.js-LTS%2010.x-green.svg)
![Compatible with SharePoint Online](https://img.shields.io/badge/SharePoint%20Online-Compatible-green.svg)
![Does not work with SharePoint 2019](https://img.shields.io/badge/SharePoint%20Server%202019-Incompatible-red.svg "SharePoint Server 2019 requires SPFx 1.4.1 or lower")
![Does not work with SharePoint 2016 (Feature Pack 2)](https://img.shields.io/badge/SharePoint%20Server%202016%20(Feature%20Pack%202)-Incompatible-red.svg "SharePoint Server 2016 Feature Pack 2 requires SPFx 1.1")
![Teams Incompatible](https://img.shields.io/badge/Teams-Incompatible-lightgrey.svg)
![Local Workbench Incompatible](https://img.shields.io/badge/Local%20Workbench-Incompatible-red.svg "This solution requires access a user's sites")
![Hosted Workbench Compatible](https://img.shields.io/badge/Hosted%20Workbench-Compatible-green.svg)


## Applies to

* [SharePoint Framework](https://docs.microsoft.com/sharepoint/dev/spfx/sharepoint-framework-overview)
* [Office 365 tenant](https://docs.microsoft.com/sharepoint/dev/spfx/set-up-your-development-environment)

## Solution

Solution|Author(s)
--------|---------
react-my-sites|João Mendes


## Version history

Version|Date|Comments
-------|----|--------
1.0.0|August 6, 2020|Initial release
1.0.1|August 29, 2020|Additional updates
1.0.2|August 30, 2020|Bug Fix, new Properties

## Minimal Path to Awesome

Please follow all the steps:

- Clone this repository
- in the command line run:
  - `npm install`
  - `gulp build`
  - `gulp bundle --ship`
  - `gulp package-solution --ship`
- Add and deploy package to your tenant's App Catalog
- Go to **API Access** - from **SharePoint Admin Center** new experience, and **Approve** the permission to use Microsoft Graph scope **Group.Read.All** and **Directory.Read.All**

## Disclaimer

**THIS CODE IS PROVIDED *AS IS* WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**

## Help

We do not support samples, but we this community is always willing to help, and we want to improve these samples. We use GitHub to track issues, which makes it easy for  community members to volunteer their time and help resolve issues.

If you encounter any issues while using this sample, [create a new issue](https://github.com/pnp/sp-dev-fx-webparts/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Abug-suspected&template=bug-report.yml&sample=react-my-sites&authors=@joaojmendes&title=react-my-sites%20-%20).

For questions regarding this sample, [create a new question](https://github.com/pnp/sp-dev-fx-webparts/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Abug-suspected&template=question.yml&sample=react-my-sites&authors=@joaojmendes&title=react-my-sites%20-%20).

Finally, if you have an idea for improvement, [make a suggestion](https://github.com/pnp/sp-dev-fx-webparts/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Abug-suspected&template=suggestion.yml&sample=react-my-sites&authors=@joaojmendes&title=react-my-sites%20-%20).



<img src="https://telemetry.sharepointpnp.com/sp-dev-fx-webparts/samples/react-my-sites" />