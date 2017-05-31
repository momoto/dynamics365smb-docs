---
title: "How to: Print Vendor 1099 Information Reports"
ms.custom: na
ms.date: "06-05-2016"
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: "article"
helpviewer_keywords: 
  - "printing, vendor 1099 information"
  - "1099 tax forms, printing"
  - "vendor 1099 information, printing"
  - "purchase orders, 1099 transactions"
ms.assetid: 5f79ec1a-44e0-4779-8a90-ecb73dc134e0
caps.latest.revision: 34
ms.author: "edupont"
manager: "terryaus"
---
# How to: Print Vendor 1099 Information Reports
In [!INCLUDE[navnow](../../ApplicationDesign/includes/navnow_md.md)], you can use the following tax forms to report 1099 transactions:  
  
-   [\($ R\_10109  Vendor 1099 Div $\)](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Canada/-$-r_10109-vendor-1099-div-$-.md) – Dividends  
  
-   [\($ R\_10111  Vendor 1099 Int $\)](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Canada/-$-r_10111-vendor-1099-int-$-.md) – Interest  
  
-   [\($ R\_10112  Vendor 1099 Misc $\)](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Canada/-$-r_10112-vendor-1099-misc-$-.md) – Miscellaneous income  
  
 The Internal Revenue Service \(IRS\) requires one or more versions of the 1099 tax form for payments to vendors. Copies of these forms must be sent to vendors annually on or before the last day of January.  
  
 The [\($ R\_10110 Vendor 1099 Information $\)](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Canada/-$-r_10110-vendor-1099-information-$-.md) report allows you to review 1099 transactions paid during a specified period. At the end of the year, you can print 1099s on preprinted forms.  
  
### To set up 1099 tax for vendors  
  
1.  In the **Search** box, enter **Purchase Orders**, and then choose the related link.  
  
2.  Select a purchase order, and then on the **Home** tab, in the **Manage** group, choose **Edit**.  
  
3.  On the **Lines** FastTab, select the **\($ T\_39\_10022 1099 Liable $\)** check box.  
  
     If the field is not visible, you must add it to the window.  
  
4.  On the **Invoicing** FastTab, fill in the fields as described in the following table.  
  
    |[!INCLUDE[bp_tablefield](../../ApplicationDesign/includes/bp_tablefield_md.md)]|[!INCLUDE[bp_tabledescription](../../ApplicationDesign/includes/bp_tabledescription_md.md)]|  
    |---------------------------------|---------------------------------------|  
    |**IRS 1099 Code**|Select the 1099 code for the vendor.|  
    |**Tax Liable**|Select to set the tax liability for the vendor.|  
  
5.  On the **Home** tab, in the **Process** group, choose **Post**.  
  
6.  Choose the **OK** button.  
  
### To print vendor 1099 information reports  
  
1.  In the **Search** box, enter **Vendor 1099 Information**, and then choose the related link.  
  
2.  On the **Vendor** FastTab, select the appropriate filters.  
  
    > [!NOTE]  
    >  To run this batch job, you must select the **Date Filter** as a filter and enter the date.  
  
3.  Choose the **Print** button to print the report or choose the **Preview** button to view it on the screen.  
  
## See Also  
 [United States Local Functionality](../../LocalFunctionalityForMicrosoftDynamicsNav2016/UnitedStates/united-states-local-functionality.md)   
 [\($ R\_10110 Vendor 1099 Information $\)](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Canada/-$-r_10110-vendor-1099-information-$-.md)   
 [\($ R\_10111  Vendor 1099 Int $\)](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Canada/-$-r_10111-vendor-1099-int-$-.md)   
 [\($ R\_10109  Vendor 1099 Div $\)](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Canada/-$-r_10109-vendor-1099-div-$-.md)   
 [\($ R\_10112  Vendor 1099 Misc $\)](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Canada/-$-r_10112-vendor-1099-misc-$-.md)   
 [\($ R\_10115  Vendor 1099 Magnetic Media $\)](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Canada/-$-r_10115-vendor-1099-magnetic-media-$-.md)   
 [\($ T\_10010 IRS 1099 Form\-Box $\)](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Canada/-$-t_10010-irs-1099-form-box-$-.md)