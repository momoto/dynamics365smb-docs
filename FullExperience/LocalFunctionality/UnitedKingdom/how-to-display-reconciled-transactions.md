---
title: "How to: Display Reconciled Transactions"
ms.custom: na
ms.date: "06-05-2016"
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: "article"
helpviewer_keywords: 
  - "reconciling, transactions"
ms.assetid: 01faf4d1-0321-48b9-b619-77077c6c2bcc
caps.latest.revision: 28
ms.author: "edupont"
manager: "terryaus"
translation.priority.ht: 
  - "en-gb"
---
# How to: Display Reconciled Transactions
You can identify whether items are reconciled in the **\($ N\_388 Bank Account Reconciliations $\)** window. You can also view the total value of all reconciled transactions.  
  
### To display reconciled transactions  
  
1.  In the **Search** box, enter **Bank Account Reconciliations**, and then choose the related link.  
  
2.  In the **\($ N\_388 Bank Account Reconciliations $\)** window, select bank account. On the **Home** tab, choose **Edit**.  
  
3.  Expand the **Lines** FastTab.  
  
4.  Fill in the fields as described in the following table.  
  
    |[!INCLUDE[bp_tablefield](../../ApplicationDesign/includes/bp_tablefield_md.md)]|[!INCLUDE[bp_tabledescription](../../ApplicationDesign/includes/bp_tabledescription_md.md)]|  
    |---------------------------------|---------------------------------------|  
    |**\($ T\_274\_4 Document No. $\)**|Specifies the document number for the transaction.|  
    |**\($ T\_274\_14 Check No. $\)**|Specifies the check number for the transaction.|  
    |**\($ T\_274\_10500 Reconciled $\)**|Specifies if the transaction has been reconciled.|  
    |**\($ T\_274\_11 Applied Entries $\)**|Specifies if the transaction has been applied to one or more bank accounts or check ledger entries.|  
  
5.  In the **\($ T\_274\_10500 Reconciled $\)** field, view the value of the reconciled transaction.  
  
6.  In the **\($ N\_380\_1040004 Total Reconciled $\)** field, view the total value of all reconciled transactions.  
  
7.  To mark transactions as **Reconciled**, select a transaction. On the **Lines** toolbar, select the **Functions** menu, and then choose **Toggle Reconciled**.  
  
8.  Choose the **OK** button.  
  
 To apply a statement line to an entry in **\($ T\_10550 BACS Ledger Entry $\)** table, you must use the **Apply Entries** function, in the same way you would do it for check ledger entries. For more information, see [\($ N\_379 Bank Acc. Reconciliation $\)](assetId:///69629c1f-013d-4c91-8175-5420a49876a7) and [How to: Match Bank Statement Lines with Bank Account Ledger Entries](../../Finance/how-to-match-bank-statement-lines-with-bank-account-ledger-entries.md).  
  
## See Also  
 [\($ R\_10555 Bank Acc. Recon. Statement $\)](../../LocalFunctionalityForMicrosoftDynamicsNav2016/UnitedKingdom/-$-r_10555-bank-acc.-recon.-statement-$-.md)   
 [United Kingdom Local Functionality](../../LocalFunctionalityForMicrosoftDynamicsNav2016/UnitedKingdom/united-kingdom-local-functionality.md)   
 [Reconcile Bank Accounts](../../Finance/reconcile-bank-accounts.md)