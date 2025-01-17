---
title: "Tableau Integration"
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

description: "Learn how to integrate your Tableau dashboard KPIs directly with Viva Goals to automate OKR success measurement."
---

# Tableau integration

The Viva Goals Tableau integration allows automated real-time tracking of Objectives and Key Results (OKR) progress. 
  
Let's take this example: you have Tableau workbooks with dashboard views used to visualize the Sales team's close rate: Quarter-to-date (QTD) vs. Goal. By configuring a Tableau integration and setting up a data link within Viva Goals, you can save the hassle of connecting to any other source sales systems and reinventing the wheel. If you have already implemented all the key performance indicator (KPI) visualizations within Tableau, Viva Goals will sync the values for you, saving you time while keeping your OKRs progress up to date.

## How to enable the Tableau integration

A Viva Goals admin can enable the Tableau integration in Viva Goals. To do so, take the following steps: 

1. Navigate to the Viva Goals integrations page through **Admin > Integrations**.
  
    :::image type="content" source="../media/goals/7/viva-goals-integrations-page.png" alt-text="Integrations page in Viva Goals." lightbox="../media/goals/7/viva-goals-integrations-page.png":::

2. Enable the Tableau integration under the **Data Integrations** category.
  
    :::image type="content" source="../media/goals/7/tableau-enable-button.png" alt-text="Enabling Tableau in Viva Goals." lightbox="../media/goals/7/tableau-enable-button.png":::

3. The integration can also be disabled at any time from the same section.
  
    :::image type="content" source="../media/goals/7/tableau-disable-button.png" alt-text="Disabling Tableau in Viva Goals." lightbox="../media/goals/7/tableau-disable-button.png":::

## How to configure the Tableau connection

In the **Connections** section, select **New Connection** and in the popup that appears, follow the prompt to configure the Tableau connection either using a Personal Access Token (or) the Username & Password method.
  
  :::image type="content" source="../media/goals/7/tableau-creating-new-connection.png" alt-text="Creating a new Tableau connection in Viva Goals." lightbox="../media/goals/7/tableau-creating-new-connection.png":::

> [!NOTE]
> Personal Access Token should be available from the Tableau 2019.4 release.

Select the (**i**) information icon to know more about each field in the popup. Links to help articles are provided as required.

A connection can be Shared or made Private based on the user's preference.  

Editing a saved Tableau connection is also allowed from the same section at any time.  
  
> [!NOTE]
> In case your organization uses an on-premise Tableau Server (For example, `https://tableau.\<org-name\>.com`) and it has restrictions on what external connections can access the server, let your Viva Goals Customer Success Manager (CSM) know, so we can share the IPs that need to be permitted for establishing the connection successfully.

## How to set up the Tableau data link

Once the connection configuration is done, users can **Edit** their OKRs to set up a data link integration to directly track progress in Viva Goals from their Tableau workbooks.

> [!NOTE]
> Tableau Integration is available only for **KPI (success metric)** method of measuring OKR success and not available for **% completion** method.

1. While creating/editing an Objective or Key Result, select **Add an integration**, then select **Tableau** from the list of integrations.
  
    :::image type="content" source="../media/goals/7/zendesk-integration-from-the-list-of-integrations-in-viva-goals.png" alt-text="Selecting Zendesk from the list of data sources in Viva goals.png." lightbox="../media/goals/7/zendesk-integration-from-the-list-of-integrations-in-viva-goals.png":::

2. If a Tableau Connection isn't configured, Viva Goals allows the user to configure a connection first. If already configured, Viva Goals allows the users to proceed with setting up the data link.

In the popup that appears, follow the prompts to set up the Tableau data link integration.
Select **Workbook**, **View** (Dashboards or Standalone Worksheets), your actual **KPI** from the list of measures/dimensions available on the selected **View**.  
  
:::image type="content" source="../media/goals/7/tableau-connection-details.png" alt-text="Adding new Tableau connection to OKRs in Viva goals." lightbox="../media/goals/7/tableau-connection-details.png":::

If there are multiple instances for the KPI value, for example, you have the Sales Goal for all your sales team members as part of the Tableau View, you can choose to apply a sum/average/count on the set of values (or) filter out by a particular person or any available filter field.  

Viva Goals displays the selected value for your reference before you save the data link set up.

> [!NOTE]
> Based on Tableau REST API limitations, Viva Goals currently has visibility only into published Workbooks and Views. If any worksheets already part of a workbook are hidden, they will not display. Un-hide all worksheets from where your team would like to integrate KPIs before publishing Tableau dashboards.
  
