---
ms.date: 11/28/2017
title: "Calling Plans known issues"
ms.author: serdars
author: pamgreen
manager: serdars
ms.reviewer: mikedav, roykuntz, jastark
ms.topic: article
ms.assetid: baa3645a-0518-472e-942e-971c63ba4ca0
ms.tgt.pltfrm: cloud
ms.service: skype-for-business-online
search.appverid: MET150
ms.collection: Adm_Skype4B_Online
audience: Admin
appliesto:
- Skype for Business 
ms.localizationpriority: medium
f1.keywords:
- NOCSH
ms.custom:
- Calling Plans
description: "Learn known issues with the calling plan for PSTN Calling and what you can do about them."
---

# Calling Plans known issues

[!INCLUDE [sfbo-retirement](../../Hub/includes/sfbo-retirement.md)]

Calling Plans are a new feature found in Skype for Business Online. The following are current issues that are being tracked and actively investigated. They'll be potentially resolved when the feature is updated in future builds.
  
## Calling Plans known issues

|**Known issue**|**Comments**|
|:-----|:-----|
|Transitioning from Tech Preview licenses to production licenses for Calling Plans don't automatically update the license.  <br/> |Purchase your new licenses first so they're ready to be assigned to your users. Remove the promo (Tech Preview) license from a user, and then **IMMEDIATELY** assign the new **Domestic Calling Plan** and/or **Domestic and International Calling Plan** licenses to the user. <br/> If you're removing and adding licenses for multiple users, it's extremely important that you remove the licenses from all of the users using Windows PowerShell and then **IMMEDIATELY** assign the licenses for all of the users also using Windows PowerShell. Doing this will ensure that there's no disruption in service when handling large volumes of user license assignments. For sample PowerShell scripts, see [Assign Skype for Business and Microsoft Teams licenses](../skype-for-business-and-microsoft-teams-add-on-licensing/assign-skype-for-business-and-microsoft-teams-licenses.md).  <br/> **Note:** If you're using on-premises PSTN connectivity for hybrid users, you *only* need to assign a **Phone System** license. You should **NOT** also assign a voice Calling Plan. However, if you're enabling Calling Plans in Microsoft 365 or Office 365 for users that are in Microsoft 365 or Office 365, you need to still assign a **Domestic Calling Plan** or a **Domestic and International Calling Plan** license for those users. See [Assign Skype for Business and Microsoft Teams licenses](../skype-for-business-and-microsoft-teams-add-on-licensing/assign-skype-for-business-and-microsoft-teams-licenses.md).

> [!NOTE]
> If you need to get more telephone numbers than this, please [contact support for business products - Admin Help](https://support.office.com/article/32a17ca7-6fa0-4870-8a8d-e25ba4ccfd4b)         |
   
## Related articles
[Transferring phone numbers common questions](/microsoftteams/transferring-phone-numbers-common-questions)

[Different kinds of phone numbers used for Calling Plans](/MicrosoftTeams/different-kinds-of-phone-numbers-used-for-calling-plans)

[Manage phone numbers for your organization](/microsoftteams/manage-phone-numbers-for-your-organization/manage-phone-numbers-for-your-organization)

[Emergency calling terms and conditions](/microsoftteams/emergency-calling-terms-and-conditions)

[Skype for Business Online: Emergency Calling disclaimer label](https://download.microsoft.com/download/9/9/0/990e24c1-eb49-4b52-9306-dbd4c864ed91/emergency-calling-label-(en-us)-(v.1.0).zip)

  
 

