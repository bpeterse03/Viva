---
title: "Salesforce Integration"
ms.reviewer: 
ms.author: vsreenivasan
author: ms-vikashkoushik
manager: <TBD>
audience: Admin
f1.keywords:
- NOCSH
ms.topic: article
ms.service: viva
ms.subservice: viva-goals
ms.localizationpriority: medium
ms.collection:  
- m365initiative-viva-goals
search.appverid:
- MET150

description: "Learn how to integrate your Viva Goals OKRs with Salesforce reports."
---

# Salesforce integration

Viva Goals integrates with Salesforce, allowing you to automatically update your Objectives and Key Results (OKRs). For example, if you have a Salesforce report that tracks converted leads, with a goal in mind to increase the value of converted leads to a certain amount, implementing a Salesforce integration will automatically update your progress in Viva Goals.

## How to set up the Salesforce integration 

An admin can set up the Salesforce integration in Viva Goals. 

1. Navigate to the Viva Goals integrations page through **Admin -> Integrations**.
  
    :::image type="content" source="../media/goals/9/viva-goals-integrations-page.png" alt-text="Integrations page in Viva Goals." lightbox="../media/goals/9/viva-goals-integrations-page.png":::

2. Scroll through the list until you reach Salesforce. Select **Enable** (Or **Manage** if a connection has been made previously).
  
    :::image type="content" source="../media/goals/9/salesforce-enable-button.png" alt-text="Enabling Salesforce in Viva Goals." lightbox="../media/goals/9/salesforce-enable-button.png":::

3. Select **"New Connection"** and follow the prompts to sign into your Salesforce account.
  
    :::image type="content" source="../media/goals/9/salesforce-new-connection-button.png" alt-text="Adding new Salesforce connection in Viva Goals." lightbox="../media/goals/9/salesforce-new-connection-button.png":::

4. Select **"Next"** to finish the setup.

Viva Goals allows you to connect with multiple Salesforce accounts. Select **New connection** to add another account and differentiate them using names. These names are displayed to members when they link their OKRs to Salesforce reports.

## How to use the Salesforce integration

Once the setup is complete, users in your organization can link the success of their OKRs directly to fields in Salesforce reports.

1. While creating (or editing) an Objective or Key Result, navigate to the **Progress** section and select **Connect to a Data Source**.

2. From the list of integrations, select **Salesforce**.
  
    :::image type="content" source="../media/goals/9/select-salesforce-datasource.png" alt-text="Selecting Salesforce from the list of data sources in Viva Goals." lightbox="../media/goals/9/select-salesforce-datasource.png":::

3. Search for the name of the report you would like to connect. If you have multiple Salesforce connections, select the connection that your report is associated with before searching for the report.
  
    :::image type="content" source="../media/goals/9/salesforce-report-selection.png" alt-text="Selecting a Salesforce report in Viva Goals." lightbox="../media/goals/9/salesforce-report-selection.png":::  

4. **Select a field**: Select the field you would like to designate as the measure of success. The available fields will vary based on the configuration of the report selected.
  
    :::image type="content" source="../media/goals/9/salesforce-field-selection.png" alt-text="Selecting a Salesforce field in Viva Goals." lightbox="../media/goals/9/salesforce-field-selection.png":::

5. Select **Next** followed by **Save** to complete the update for your OKR.

You should now see a Salesforce icon next to the OKR. The OKR will sync automatically every hour, but to refresh it manually, go to the cloud icon and select **Sync**.

