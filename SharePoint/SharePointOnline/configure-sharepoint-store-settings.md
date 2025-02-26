---
title: "Configure settings for the SharePoint Store"
ms.reviewer: 
ms.author: mikeplum
author: MikePlumleyMSFT
manager: serdars
recommendations: true
audience: Admin
f1.keywords:
- NOCSH
ms.topic: article
ms.service: sharepoint-online
ms.localizationpriority: medium
search.appverid:
- SPO160
- MET150
ms.assetid: 6b806fb8-9295-441d-b954-07009021dc48
description: "Learn how to allow or prevent users from getting apps from the SharePoint Store, and how to manage app requests."
---

# Configure settings for the SharePoint Store

The [SharePoint Store](https://appsource.microsoft.com/marketplace/apps?product=sharepoint) is a public marketplace that offers apps for Microsoft 365, as well as Dynamics 365 and Power Platform. Site users can access the SharePoint Store directly from a SharePoint site to browse for and add third-party apps. If a SharePoint environment has been configured to prevent users from getting apps from the SharePoint Store, users can still browse for and request apps. These requests are added to the App Requests list in the App Catalog.

Learn more
  
- [Add an app to a site](https://support.office.com/article/dd98e50e-d3db-4ecb-9bb7-82b189822d43)
- [Office Store and SharePoint Store Terms of Use](https://support.office.com/article/64c7f343-16b5-40bb-b39f-66c9d1c4d405)
  
## Specify whether users can get apps from the SharePoint Store
<a name="__top"> </a>

By default, SharePoint is configured to allow users to get or request apps from the SharePoint Store. The option to change this setting will not be enabled if you have not yet created an App Catalog site. For information about how to create an App Catalog site, see [Use the App Catalog to make custom business apps available for your SharePoint environment](use-app-catalog.md).
  
Even if you choose not to allow users to add apps from the SharePoint Store, they will still be able to browse the SharePoint Store and request apps.
  
1. Go to the [More features page of the new SharePoint admin center](https://admin.microsoft.com/sharepoint?page=classicfeatures&modern=true), and sign in with an account that has [admin permissions](./sharepoint-admin-role.md) for your organization.

   > [!NOTE]
   > If you have Office 365 Germany, [sign in to the Microsoft 365 admin center](https://go.microsoft.com/fwlink/p/?linkid=848041), then browse to the SharePoint admin center and open the More features page.
   > 
   > If you have Office 365 operated by 21Vianet (China), [sign in to the Microsoft 365 admin center](https://go.microsoft.com/fwlink/p/?linkid=850627), then browse to the SharePoint admin center and open the More features page.

2. Under **Apps**, select **Open**, and then select **Configure Store Settings**.
    
3. Next to **App Purchases**, do one of the following:
    
   - If you want users to be able to add apps, select **Yes**. (The setting uses the word "purchases" and mentions paid apps, but all apps in the SharePoint Store are now free.)
    
   - If you do not want users to be able to get third-party apps, select **No**. 
    
## View or manage app requests
<a name="__top"> </a>

When users request an app, they are requesting that an admin get that app on their behalf. In an app request, users can request a specific number of licenses, and they can provide a business justification for why they need the app. App requests are saved to the App Requests list in the App Catalog site.
  
1. Go to the [More features page of the new SharePoint admin center](https://admin.microsoft.com/sharepoint?page=classicfeatures&modern=true), and sign in with an account that has [admin permissions](./sharepoint-admin-role.md) for your organization.

   > [!NOTE]
   > If you have Office 365 Germany, [sign in to the Microsoft 365 admin center](https://go.microsoft.com/fwlink/p/?linkid=848041), then browse to the SharePoint admin center and open the More features page.
   > 
   > If you have Office 365 operated by 21Vianet (China), [sign in to the Microsoft 365 admin center](https://go.microsoft.com/fwlink/p/?linkid=850627), then browse to the SharePoint admin center and open the More features page.

2. Under **Apps**, select **Open**, and then select **Configure Store Settings**.
    
3. Next to **App Requests**, select the link **Select here to view app requests**.
    
4. In the **App Requests** list, select a request, and then select **Edit**.
    
5. In the **Status** list, do one of the following: 
    
   - To approve the request, select **Approved**. If you approve the app request and want to add the app immediately, select the link next to **View App Details**. The app details page in the SharePoint Store will open in another tab in your browser, and you can follow the steps to add the app. 
    
   - To decline the request, select **Declined**.
    
6. On the app request form, add any comments in the **Approvers Comments** field, and then select **Save**.
    
7. After the status has been changed to **Approved**, if you didn't add the app in the approval process, users need to add it to the site. See [Add an app to a site](https://support.office.com/article/dd98e50e-d3db-4ecb-9bb7-82b189822d43).
    
Site users who request apps can view their requests by going to **Settings** \> **Add an app** \> **Your Requests**.
  
## Specify whether to allow apps for Office to start in documents
<a name="__top"> </a>

Documents stored on sites may contain apps for Office from several sources. You can specify whether or not you want to allow these apps to work when documents are opened in the browser.
  
1. Go to the [More features page of the new SharePoint admin center](https://admin.microsoft.com/sharepoint?page=classicfeatures&modern=true), and sign in with an account that has [admin permissions](./sharepoint-admin-role.md) for your organization.

   > [!NOTE]
   > If you have Office 365 Germany, [sign in to the Microsoft 365 admin center](https://go.microsoft.com/fwlink/p/?linkid=848041), then browse to the SharePoint admin center and open the More features page. <br>If you have Office 365 operated by 21Vianet (China), [sign in to the Microsoft 365 admin center](https://go.microsoft.com/fwlink/p/?linkid=850627), then browse to the SharePoint admin center and open the **More features** page.

2. Under **Apps**, select **Open**, and then select **Configure Store Settings**.
 
3. Next to **Apps for Office from the Store**, do one of the following:
    
   - If you want to allow apps for Office to start when documents are opened in the browser, select **Yes**. 
    
   - If you do not want to allow apps for Office to start when documents are opened in the browser, select **No**.