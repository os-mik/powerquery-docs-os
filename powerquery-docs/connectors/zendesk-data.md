---
title: Power Query Zendesk Data (Beta) connector
description: Provides basic information and prerequisites for the Zendesk Data (Beta) connector, describes the connection process, and discusses limitations and issues you might encounter.
author: DougKlopfenstein
ms.topic: conceptual
ms.date: 4/5/2024
ms.author: dougklo
ms.subservice: connectors
---

# Zendesk Data (Beta) Power Query custom connector

> [!NOTE]
>The following connector article is provided by Zendesk, the owner of this connector and a member of the Microsoft Power Query Connector Certification Program. If you have questions regarding the content of this article or have changes you would like to see made to this article, visit the Zendesk website and use the support channels there.

## Summary

| Item | Description |
| ---- | ----------- |
| Release State | Beta |
| Products | Power BI (Semantic models) |
| Authentication Types Supported | Zendesk account |

## Prerequisites

Before you can sign in to Zendesk, you must have a Zendesk account (username/password).

## Capabilities Supported

* Import

## Connect to Zendesk data

To connect to Zendesk data:

1. Select **Get Data** from the **Home** ribbon in Power BI Desktop. Select **Online Services** from the categories on the left, select **Zendesk Data (Beta)**, and then select **Connect**.

   :::image type="content" source="./media/zendesk/get-data-zendesk-data.png" alt-text="Image with Online Services category and the Zendesk connector highlighted.":::

2. If this is the first time you're getting data through the Zendesk Data connector, a preview connector notice will be displayed. Select **Don't warn me again with this connector** if you don't want this message to be displayed again, and then select **Continue**.

3. Enter the Zendesk URL location that you want to access, and the select **OK**.

   :::image type="content" source="./media/zendesk/zendesk-url.png" alt-text="Image with Zendesk URL location filled out and ready to select OK.":::

4. To sign in to your Zendesk account, select **Sign in**.

   ![Image with Zendesk account highlighted, and showing the sign in button.](./media/zendesk/sign-in.png)

5. In the Zendesk window that appears, provide your credentials to sign in to your Zendesk account.

   :::image type="content" source="./media/zendesk/zendesk-sign-in.png" alt-text="Image with the sign in screen to Zendesk.":::

6. Select **Sign in**.

7. Once you've successfully signed in, select **Connect**.

   :::image type="content" source="./media/zendesk/signed-in.png" alt-text="Image with the user signed in and ready to connect.":::

8. In **Navigator**, select the information you want, then either select **Load** to load the data or **Transform Data** to continue transforming the data in Power Query Editor.
   
   :::image type="content" source="./media/zendesk/navigator.png" alt-text="Image with the navigator after the user signed in.":::

## Next steps

You may also find the following information useful:

* [Using the Power BI Connector by Zendesk](https://support.zendesk.com/hc/en-us/articles/6700481028634-Using-the-Power-BI-Connector-by-Zendesk-Beta)
