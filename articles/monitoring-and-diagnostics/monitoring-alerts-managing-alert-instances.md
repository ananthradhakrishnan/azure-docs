---
title: Managing Alert Instances
description: Managing alert instances across Azure
author: anantr
services: monitoring
ms.service: azure-monitor
ms.topic: conceptual
ms.date: 09/24/2018
ms.author: anantr
ms.component: alerts
---

# Overview
This article shows you how to manage your alert instances across Azure, and how to get the contextual information that will help you manage the alert.
1. In the [portal](https://portal.azure.com/), select **Monitor** and under the MONITOR section - choose **Alerts**.  
    ![Monitoring](./media/monitoring-alerts-managing-alerts-instances/monitoring-alerts-managing-alert-instances-toc.jpg)

1.	You will land on the **Alerts Summary** page, which gives you an overview of all your alert instances across Azure. You can modify the summary view by selecting **multiple subscriptions** (a maximum of 5) or by filtering across **resource groups**, specific **resources** or **time ranges**. Click on either Total Alerts or any of the severity bands to go to the list view for your alerts.   
    ![Alerts Summary](./media/monitoring-alerts-managing-alerts-instances/alerts-summary.jpg)
 
1.	You will land on the **All Alerts** page, where you will see all the alert instances across Azure listed out. If you’re coming to the portal from an alert notification, you can use the filters available to narrow in on that specific alert instance. (**Note**: if you came to the page by clicking on any of the severity bands, the list will be pre-filtered for that severity when you land). APart from the filters available on the previous page, you can now also filter on the basis of monitor service (e.g. Platform for metrics), monitor condition (fired or resolved), severity, alert state (new/acknowledged/closed) or the smart group id.
    ![All Alerts](./media/monitoring-alerts-managing-alerts-instances/all-alerts.jpg)
 
1.	Clicking on the any alert instance opens up the **Alert Details** page, allowing you to deep-dive into information about that specific alert instance.   
![Alert Details](./media/monitoring-alerts-managing-alerts-instances/alert-details.jpg)  
