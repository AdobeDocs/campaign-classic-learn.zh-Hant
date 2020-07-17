---
title: 控制面板
seo-title: 控制面板
description: 「控制面板」可讓您依例項監視和管理SFTP儲存空間，並允許列出IP位址。
seo-description: 「控制面板」可讓您依例項監視和管理SFTP儲存空間，並允許列出IP位址。
feature: Control Panel
topics: Control Panel
kt: 3262
doc-type: feature video
activity: use
team: PM
translation-type: tm+mt
source-git-commit: 37c36a52fb6fc7a5ccfe5d82dc9a32397b9a7d89
workflow-type: tm+mt
source-wordcount: '441'
ht-degree: 5%

---


# [!UICONTROL Control Panel]

>[!NOTE]
>
>Adobe Campaign文[!UICONTROL whitelist]件中的「[!UICONTROL blacklist]」和「」已取代[!UICONTROL allow list]「」和[!UICONTROL block list]「」。
>產品UI、選項名稱、內部程式碼以及教學課程影片中可能仍會出現這些詞語。 在即將發行的「控制面板」版本中，將會取代它們。

可 [!UICONTROL Control Panel] 讓Adobe Campaign管理員監控關鍵資產並執行管理工作，例如依例項或IP位址管理SFTP [!UICONTROL allow list] 儲存。

## 存取 [!UICONTROL Control Panel]

若要存取「控制面板」，請前往Experience Cloud首頁： [https://experiencecloud.adobe.com](https://experiencecloud.adobe.com):

* **[!UICONTROL Experience Cloud Home]** > **[!UICONTROL Quick Access]**

   或
* **[!UICONTROL Experience Cloud Home]**  > [!UICONTROL Solution picker]: **促銷活動** > **[!UICONTROL Control Panel]卡片&#x200B;**

   或

* 直接從URL: [https://experience.adobe.com/#/controlpanel](https://experience.adobe.com/#/controlpanel)

## 必要條件

開始之前，請先完成下列必要條件：

### 確認 [!DNL IMS Org ID]

你要瞭解你的 [!DNL IMS org ID]。 以下視訊說明您可以在何處查閱例項 [!DNL IMS org ID]。

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*檢[!DNL IMS Org ID]查（00:26分鐘）*

### 管理員權限

必須擁有管理員權限才能訪問 [!UICONTROL Control Panel]。
以下影片說明如何新增管理員至促銷活動例項

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*如何將管理員新增至產品設定檔「[!UICONTROL Administrators]」，以便能夠使用([!UICONTROL Control Panel]01:03分鐘)*

## [!UICONTROL Control Panel] 教學課程

* **管理SFTP伺服器**

   *瞭解如何監控伺服器容量、[!UICONTROL allow list]IP地址和添加SSH密鑰*

   * [監控伺服器容量、允許列出IP地址和添加SSH密鑰](/help/acc/monitoring-campaign-classic/control-panel/monitoring-server-capacity-allow-listing-adding-ssh-key.md)
   * [生成SSH密鑰](/help/acc/monitoring-campaign-classic/control-panel/generate-ssh-key.md)
   * [連接到SFTP伺服器](/help/acc/monitoring-campaign-classic/control-panel/connect-to-sftp-server.md)

* **[委派子網域](/help/acc/monitoring-campaign-classic/control-panel/subdomain-delegation.md)**

   *瞭解如何將子網域完全委派至[!UICONTROL Adobe Campaign]*

* **[新增SSL憑證](/help/acc/monitoring-campaign-classic/control-panel/adding-ssl-certificates.md)**

   *瞭解如何使用「控制面板」新增SSL憑證以保護您的子網域。*

* **[管理SSL憑證](/help/acc/monitoring-campaign-classic/control-panel/managing-ssl-certificates.md)**

   *瞭解如何檢視子網域的SSL憑證狀態，以及要求續約。*

* **[新增URL權限](/help/acc/monitoring-campaign-classic/control-panel/adding-url-permissions.md)**

   *如何新增一些外部URL至授權URL清單，讓您的例項可以連線至這些URL。*

* **[IP 允許執行個體存取清單](/help/acc/monitoring-campaign-classic/control-panel/ip-allow-listing.md)**

   *瞭解如何依據IP位址範圍設定新的例[!UICONTROL allow listing]項連線。*

* **[Google TXT 記錄管理](/help/acc/monitoring-campaign-classic/control-panel/google-txt-record-management.md)**

   *瞭解如何將網站驗[!DNL Google TXT]證記錄新增至您用來透過網站傳送電子郵件至地址[!DNL GMAIL]的所有子網域[!UICONTROL Campaign Control Panel]。*

* **GPG密鑰管理**

   *瞭解如何在指定的促銷活動例項上產生和安裝公開／私密金鑰對，以加密傳出資料，以及在促銷活動例項上匯入和安裝公開金鑰，以解密傳入資料：*

   * [生成並安裝用於資料加密的GPG密鑰](./gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.md)
   * [使用GPG密鑰加密資料](./gpg-key-management/using-a-gpg-key-to-encrypt-data.md)
   * [解密資料](./gpg-key-management/decrypting-data.md)

* **[控制面板疑難排解](/help/acc/monitoring-campaign-classic/control-panel/trouble-shooting.md)**

   *瞭解如何疑難排解[!UICONTROL Control Panel]*

## 其他資源

* [控制面板說明中心](https://docs.adobe.com/content/help/zh-Hant/control-panel/using/control-panel-home.html)