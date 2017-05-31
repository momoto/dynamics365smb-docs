---
title: "How to: Flush Components According to Operation Output"
ms.custom: na
ms.date: "03-03-2017"
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: "article"
helpviewer_keywords: 
  - "output, flushing components"
  - "flushing, by operation"
  - "flushing, method"
ms.assetid: 3ab97069-e4ba-4da1-89b0-09e99a338495
caps.latest.revision: 6
ms.author: "sgroespe"
manager: "terryaus"
translation.priority.ht: 
  - "da-dk"
  - "de-at"
  - "de-ch"
  - "de-de"
  - "en-au"
  - "en-ca"
  - "en-gb"
  - "en-in"
  - "en-nz"
  - "es-es"
  - "es-mx"
  - "fi-fi"
  - "fr-be"
  - "fr-ca"
  - "fr-ch"
  - "fr-fr"
  - "is-is"
  - "it-ch"
  - "it-it"
  - "nb-no"
  - "nl-be"
  - "nl-nl"
  - "ru-ru"
  - "sv-se"
---
# How to: Flush Components According to Operation Output
For items that are set up with backward flushing method, the default behavior is to calculate and post component consumption when you change the status of a released production order to **Finished**. For more information, see [\($ T\_27\_5417 Flushing Method $\)](../Topic/\($%20T_27_5417%20Flushing%20Method%20$\).md).  
  
 If you also define routing link codes, then calculation and posting occurs when each operation is finished, and the quantity that was actually consumed in the operation is posted. For more information, see [How to: Create Routing Links](../DesignAndEngineering/how-to-create-routing-links.md).  
  
 For example, if a production order to produce 800 meters requires 8 kg of a component, then when you post 200 meters as output, 2 kg are automatically posted as consumption.  
  
 This functionality is useful for the following reasons:  
  
-   **Inventory Valuation** \- Value entries for output and consumption are created in parallel as the production order progresses. Without routing link codes, the inventory value will increase as output is posted and then decrease at a later point in time when the value of component consumption is posted together with the finished production order.  
  
-   **Inventory Availability** \- With gradual consumption posting, the availability of component items is more up\-to\-date, which is important to maintain the internal balance between demand and supply. Without routing link codes, other demands for the component may believe that it is available as long as it is pending a delayed consumption posting.  
  
-   **Just\-in\-Time** – With the ability to customize products to customer requests, you can minimize waste by making sure that work and system changes only occur when it is necessary.  
  
 The following procedure shows how to combine backward flushing and routing link codes so that the quantity that is flushed for each operation is proportional to the actual output of the finished operation.  
  
### To flush components according to operation output  
  
1.  In the **Search** box, enter **Items**, and then choose the related link.  
  
2.  Select the component that you want to set up. On the **Home** tab, in the **Manage** group, choose **Edit**.  
  
3.  On the **Replenishment** FastTab, in the **Flushing Method** field, select **Forward**.  
  
    > [!NOTE]  
    >  Select **Pick\+ Forward** if the component is used in a location that is set up for directed put\-away and pick.  
  
4.  In the **Search** box, enter **Routings**, and then choose the related link.  
  
5.  Define routing link codes for every operation that consumes the component. For more information, see [How to: Create Routing Links](../DesignAndEngineering/how-to-create-routing-links.md).  
  
6.  In the **Search** box, enter **Production BOM**, and then choose the related link.  
  
7.  Define routing link codes from each instance of the component to the operation where it is consumed. For more information, see [How to: Create Routing Links](../DesignAndEngineering/how-to-create-routing-links.md).  
  
    > [!IMPORTANT]  
    >  The component must have a routing link to the last operation in the routing.  
  
## See Also  
 [\($ T\_5407\_19 Routing Link Code $\)](../Topic/\($%20T_5407_19%20Routing%20Link%20Code%20$\).md)   
 [\($ T\_27\_5417 Flushing Method $\)](../Topic/\($%20T_27_5417%20Flushing%20Method%20$\).md)   
 [How to: Create Routing Links](../DesignAndEngineering/how-to-create-routing-links.md)