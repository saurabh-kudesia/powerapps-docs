---
title: What's new in PowerApps | Microsoft Docs
description: Updates to PowerApps, organized by release date
services: ''
suite: powerapps
documentationcenter: na
author: skjerland
manager: kfile
editor: ''
tags: ''

ms.service: powerapps
ms.devlang: na
ms.topic: article
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 03/21/2018
ms.author: sharik

---
# What's new in PowerApps
For information about known limitations, see [Common issues and resolutions](common-issues-and-resolutions.md).

> [!NOTE]
> Releases are rolled out over several days. New or updated functionality may not appear immediately.

## Mar. 21
1. Create [model-driven apps](../model-driven-apps/model-driven-app-overview.md), which start with your data model and build up from the shape of your core business data and processes in the Common Data Service to model forms, views, and other components. Model-driven apps automatically generate great UI that is responsive across devices.
2. [Create a database](../../administrator/create-database.md) on the latest version of the Common Data Service in an environment.
3. The Common Data Service for Apps now includes:

    - **Additional data types** support more complex entity definitions and provide richer experiences. (Applies to canvas and model-driven apps.)
    - [Create and customize entities](../common-data-service/data-platform-create-entity.md) in the Common Data Service for Apps right from the PowerApps site. The **refreshed experience** includes improved performance, a more user-friendly UI, and helpful features such as in-line creation of option sets. (Applies to canvas and model-driven apps.) 
    - Create **server-side business rules** for validating data entered into the Common Data Service for Apps. (Applies to canvas and model-driven apps.)
    - Create **calculated and rollup fields** in Common Data Service for Apps entities directly from the PowerApps site. (Applies to canvas and model-driven apps.)  
    - Developers can use the Common Data Service for Apps **Software Development Kit** (SDK) to create code-based customizations for the Common Data Service. 
    - Advanced users can access data stored in the Common Data Service for Apps through a new **OData Web API**. 
    - [Import data](../common-data-service/data-platform-cds-newentity-pq.md) into Common Data Service with **Power Query**. Use Power Query on the web to directly import data to the Common Data Service for Apps from multiple sources

## Mar. 5
1. Add (and delete) [attachments](controls/control-attachments.md) to SharePoint lists.
2. Open external [PDF](controls/control-pdf-viewer.md) files in a web browser. (Experimental feature)

## Feb. 12
* The volume control for embedded [video](controls/control-audio-video.md) and [audio](controls/control-audio-video.md) playback is now inline. To mute playback, instead of clicking or tapping a button, users must now use the volume control to lower the volume.

## Feb. 7
1. Removed the Zoom, Brightness, and Contrast properties from the [Camera](controls/control-camera.md) and [Barcode scanner](controls/control-barcodescanner.md) controls.
2. Fixed the issue where Clear buttons on [Text input](controls/control-text-input.md) controls limit the space alloted for user input. As a result of this fix, the [Clear](controls/control-text-input.md#additional-properties) property of a Text input control is supported only in Microsoft Edge (latest version) and Internet Explorer 11 web browsers.
3. Added accessibility enhancements to [multimedia](add-images-pictures-audio-video.md) controls.

## Jan. 31
1. Add closed captions to [Video](controls/control-audio-video.md) controls.
2. Improved error handling in [PDF Viewer](controls/control-pdf-viewer.md) controls.

## Jan. 18
1. PowerApps for iOS and Android now supports integration with Microsoft Authenticator.
2. A [combo box](controls/control-combo-box.md) replaces the [SharePoint lookup control](sharepoint-lookup-fields.md) in forms and a new [data card](working-with-cards.md) template for single-select lookup fields is selected by default in PowerApps Studio.
3. Within a [combo box](controls/control-combo-box.md), see all items in a long list with enhanced Read mode.
4. Control the size of the local record limit store up to a maximum of 2000 records in [non-delegable queries](delegation-overview.md#non-delegable-limits). (Experimental feature)

## Jan. 5
* Act on data right from your Power BI report or dashboard by integrating a [PowerApps custom visual (preview release)](https://powerapps.microsoft.com/blog/powerbi-powerapps-visual/), which pulls contextual data from your Power BI report.

## Dec. 8
1. [Condition templates](working-with-rules.md) for rules infer common properties of a control (such as **Text** or **Value**).
2. Stop displaying the [**Defining actions** confirmation dialog box](working-with-rules.md) when defining rule actions.

## Nov. 13
1. Select multiple values for the same field in SharePoint lists.
2. [View and download attachments](controls/control-attachments.md) in SharePoint lists.
3. [Customize SharePoint list forms](customize-list-form.md) using PowerApps.

## Nov. 10
* [Rename rules](working-with-rules.md) in an app and show rules when the selected control is in the rule condition.

## Oct. 30
1. [Show all rules](working-with-rules.md) in an app, not just those for the selected control.
2. Add icons that app creators requested the most.
3. Improved performance of apps on Android and iOS devices.
