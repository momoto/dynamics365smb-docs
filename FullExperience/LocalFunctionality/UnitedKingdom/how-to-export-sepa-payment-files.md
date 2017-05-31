---
title: "How to: Export SEPA Payment Files"
ms.custom: na
ms.date: "06-05-2016"
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: "article"
ms.assetid: 56976c38-83af-4db8-a582-3d6beaec04e8
caps.latest.revision: 4
ms.author: "edupont"
translation.priority.ht: 
  - "en-gb"
---
# How to: Export SEPA Payment Files
The following procedure describes how to export a SEPA payment file, one of the payment options supported by [!INCLUDE[navnow](../../ApplicationDesign/includes/navnow_md.md)]. The procedure describes how to create a payment for a vendor, but the same steps also apply to creating payments for a customer.  
  
 Before starting this procedure, you need to specify the following information on the vendor card:  
  
-   **\($ T\_23\_47 Payment Method Code $\)**: Bank  
  
-   **\($ T\_23\_288 Preferred Bank Account $\)**  
  
 In addition, you must specify IBAN and SWIFT Code information for the recipient bank.  
  
### To export a SEPA payment file  
  
1.  In the **Search** box, enter **Bank Accounts**, and then choose the related link.  
  
2.  Select the bank through which you will make the SEPA payment, and on the **Home** tab, in the **Manage** group, choose **Edit**.  
  
3.  On the **Transfer** FastTab, fill in the following fields:  
  
    -   **\($ T\_270\_111 SWIFT Code $\)**  
  
    -   **\($ T\_270\_110 IBAN $\)**  
  
    -   **\($ T\_270\_1210 Payment Export Format $\)**: SEPA  
  
    -   **\($ T\_270\_115 SEPA CT Msg. ID No. Series $\)**  
  
     Close the window.  
  
4.  In the **Search** box, enter **Payment Journals**, and then choose the related link.  
  
5.  Select a batch in the **Batch Name** field. In the **\($ N\_251 General Journal Batches $\)** window, for the batch, select the **\($ T\_232\_11 Allow Payment Export $\)** check box.  
  
     Choose the **OK** button.  
  
6.  In the **\($ N\_256 Payment Journal $\)** window, create a payment line.  
  
7.  Fill in the fields as described in the following table.  
  
    |[!INCLUDE[bp_tablefield](../../ApplicationDesign/includes/bp_tablefield_md.md)]|[!INCLUDE[bp_tabledescription](../../ApplicationDesign/includes/bp_tabledescription_md.md)]|  
    |---------------------------------|---------------------------------------|  
    |**\($ T\_81\_7 Document No. $\)**|Specifies the document number for the journal line.|  
    |**\($ T\_81\_3 Account Type $\)**|Select the account type as **Vendor**.|  
    |**\($ T\_81\_4 Account No. $\)**|Specifies the code of the vendor that you selected in the **\($ N\_26 Vendor Card $\)** window.|  
    |**\($ T\_81\_288 Recipient Bank Account $\)**|Specifies the bank account that you have set on the vendor card as the preferred bank.|  
    |**\($ T\_81\_12 Currency Code $\)**|Specifies the currency code.|  
    |**\($ T\_81\_13 Amount $\)**|Specifies the total amount including VAT.|  
  
8.  On the **Home** tab, in the **Process** group, choose **Export Payments to File**.  
  
9. In the case of error, review the errors listed in the **Payment File Errors** FactBox, and take the appropriate action.  
  
 You can export a line again if needed. On the **Home** tab, in the Bank group, choose **Export Payments to File**, and then choose **Yes**.  
  
## See Also  
 [How to: Export BACS Files](../../LocalFunctionalityForMicrosoftDynamicsNav2016/UnitedKingdom/how-to-export-bacs-files.md)