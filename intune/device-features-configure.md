---
# required metadata

title: Configure Microsoft Intune device feature settings
titleSuffix:
description: Learn how to use Microsoft Intune to configure features on devices you manage.
keywords:
author: vhorne
ms.author: victorh
manager: dougeby
ms.date: 03/02/2018
ms.topic: article
ms.prod:
ms.service: microsoft-intune
ms.technology:

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
ms.reviewer: heenamac
ms.suite: ems
#ms.tgt_pltfrm:
ms.custom: intune-azure

---

#Configure device feature settings in Microsoft Intune

[!INCLUDE[azure_portal](./includes/azure_portal.md)]

Device features let you control features on iOS and macOS devices like AirPrint, notifications, and shared device configurations.

Use the information in this article to learn the basics about configuring device feature profiles, and then read additional articles for each platform to learn about device specifics.

## Create a device profile containing device feature settings

1. Sign into the [Azure portal](https://portal.azure.com).
2. Choose **All services** > **Intune**. Intune is located in the **Monitoring + Management** section.
3. On the **Intune** page, choose **Device configuration**.
2. On the **Device configuration** page under the **Manage** section, choose **Profiles**.
3. On the profiles page, choose **Create profile**.
4. On the **Create profile** page, enter a **Name** and **Description** for the device features profile.
5. From the **Platform** drop-down list, select the device platform to which you want to apply the settings. Currently, you can choose one of the following platforms for device features:
	- **iOS**
	- **macOS**
6. From the **Profile type** drop-down list, choose **Device features**.
7. Depending on the platform you chose, the settings you can configure is different. Go to one of the following articles for detailed settings for each platform:
	- [AirPrint settings for iOS and MacOS](air-print-settings-ios-macos.md)
 	- [AirPlay settings for iOS](airplay-settings-ios.md)
	- [Home screen layout settings for iOS](home-screen-settings-ios.md)
	- [App notification settings for iOS](app-notification-settings-ios.md)
	- [Shared device configuration settings for iOS](shared-device-settings-ios.md)
	- [Configure Intune for iOS device Single Sign-on](sso-ios.md)
	- [Web content filter settings for iOS](web-content-filter-settings-ios.md)

8. When you're done, select **OK**, go back to the **Create profile** page, and choose **Create**.

The profile is created and appears on the profiles list page.
## Next steps

If you want to assign this profile to groups, see [How to assign device profiles](device-profile-assign.md).
