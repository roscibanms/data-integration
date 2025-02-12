---
title: "Migrate, restore, or take over an on-premises data gateway"
description: Learn how to move a gateway to a new computer, recover a damaged gateway, or take over ownership of a gateway.
author: arthiriyer
manager: kvivek
ms.reviewer: kvivek

ms.prod: on-premises-data-gateway
ms.technology:
ms.topic: conceptual
ms.date: 07/15/2019
ms.author: arthii


LocalizationGroup: Gateways
---

# Migrate, restore, or take over an on-premises data gateway

Run the gateway installer on a computer where you want to migrate, restore, or take over an on-premises data gateway.

If you're restoring the gateway on the computer that has the original gateway installation, you must first uninstall the gateway on that computer.

> [!NOTE]
> If you [remove or delete a gateway cluster](service-gateway-manage.md#remove-or-delete-an-on-premises-data-gateway) in any of the cloud services, you will not be able to restore it.

1. Download the gateway and install it. For more information, see [Install an on-premises data gateway](service-gateway-install.md).

1. After you've signed in to your Office 365 account, register the gateway. Select **Migrate, restore, or takeover an existing gateway** > **Next**.

    ![Choosing to migrate, restore, or take over a gateway.](media/service-gateway-migrate/register-gateway.png)

1. Select from the available clusters and gateways, and enter the recovery key for the selected gateway. You created and safely stored the recovery key when you originally installed the gateway. For more information, see step 8 in [Install an on-premises data gateway](service-gateway-install.md).

1. Select **Configure**.

    ![Configuring the migration, restoration, or takeover of a gateway.](media/service-gateway-migrate/migrate-restore-takeover.png)

After the configuration finishes, the process of migrating, restoring, or taking over is complete.

## Next steps

* [Troubleshoot the on-premises data gateway](service-gateway-tshoot.md)


[!INCLUDE[footer-include](../includes/footer-banner.md)]