---
title: "Show or hide form elements with PowerApps | MicrosoftDocs"
description: "Learn how to display or hide from elements, such as tabs, sections, or fields"
ms.custom: ""
ms.date: 04/26/2018
ms.reviewer: ""
ms.service: "crm-online"
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
applies_to: 
  - "Dynamics 365 (online)"
  - "Dynamics 365 Version 9.x"
  - "powerapps"
author: "Mattp123"
ms.assetid: 7b9e8dc2-229c-455f-ae18-49e8d879ff71
caps.latest.revision: 63
ms.author: "matp"
manager: "kvivek"
search.audienceType: 
  - customizer
search.app: 
  - D365CE
---
# Show or hide form elements

[!INCLUDE [cc-applies-to-powerapps-and-update-9-0-0](../includes/cc-applies-to-powerapps-and-update-9-0-0.md)]<br/>[!INCLUDE [cc_applies_to_on-prem-9_0_0](../includes/cc_applies_to_on-prem-9_0_0.md)]

 Several types of form elements have the option to be shown or hidden by default. Tabs, sections, fields, iFrames, and web resources all provide this option. Using form scripts or business rules the visibility of these elements can be controlled to create a dynamic form to provide a user interface that adapts to conditions in the form.  
  
> [!NOTE]
>  Hiding form elements is not a recommended way to enforce security. There are several ways people can view all the elements and data in the form when elements are hidden. 
  
 Rather than designing forms that depend on scripts to control visibility of options, consider whether a business process flow, a dialog, or switching to a different form may be better suited to meet your requirements. If you do use scripts, make sure that any element that might be hidden is hidden by default. Only show it with scripts when your logic calls for it. This way it will not be displayed in presentations that do not support scripts.  

### See also

[Overview of the form editor interface](form-editor-user-interface-legacy.md)
