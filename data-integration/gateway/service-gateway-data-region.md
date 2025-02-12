---
title: Set the datacenter region for the on-premises data gateway
description: This article describes how to determine the datacenter region and how its value can be set.
author: arthiriyer
ms.author: arthii
manager: kvivek
ms.reviewer: kvivek
ms.prod: on-premises-data-gateway
ms.technology:
ms.topic: conceptual
ms.date: 07/15/2019
LocalizationGroup: Gateways 
---

# Set the datacenter region for the on-premises data gateway

During installation of the on-premises data gateway, you can set the datacenter region used by the gateway.

If you have registered for either Power BI or Office 365, the datacenter region by default is the region of the registered service's tenant. Otherwise, the datacenter region might be the Azure region closest to you.

![On-premises data gateway datacenter region.](media/service-gateway-data-region/data-center-region.png)

> [!NOTE]
> For soverign clouds, we currently only support installing gateways in the default PowerBI region of your tenant. The region picker on the installer is only supported for Public cloud.

## Restore, migrate, or take over a gateway in a non-default region 

If you want to restore, migrate, or take over a gateway in a non-default Power BI region: 

![Setting the gateway datacenter region after installation.](media/service-gateway-data-region/restore-change-region.png)

## Current datacenter region

To find the current datacenter region after you install the gateway:

1. Open the [on-premises data gateway app](service-gateway-app.md) and sign in to your account.
1. In the **Status** tab, your datacenter region appears under **Logic Apps, Azure Analysis Services**.

   ![the Status tab highlighting the current datacenter region.](media/service-gateway-data-region/gateway-data-center-region.png)

For more information about setting the datacenter region for your resources, [watch this video](https://guyinacube.com/2018/01/power-bi-azure-analysis-services-gateway-data-region/).

## Next steps

* [Adjust communications settings](service-gateway-communication.md)


[!INCLUDE[footer-include](../includes/footer-banner.md)]