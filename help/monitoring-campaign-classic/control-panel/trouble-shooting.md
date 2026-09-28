---
title: 控制面板疑難排解
description: 「控制面板」可以讓您依執行個體及允許清單IP位址監視及管理SFTP儲存。
feature: Control Panel
jira: KT-2938
doc-type: article
activity: use
team: PM
source-git-commit: 35e036486c5b533b54b3f626d88734e9a9fc3b8a
workflow-type: tm+mt
source-wordcount: '353'
ht-degree: 67%
---

# 疑難排解 [!UICONTROL Control Panel]

## 登入和首頁

### 症狀：無法登入 Experience Cloud

**該做什麼：**
使用者必須找到自己的 IMS Org ID (xxx)。 系統管理員需要將使用者新增到他們想要管理的每個執行個體的產品設定檔「Campaign-xxx-Admins」。 如果使用者是所有執行個體的管理員，則他們仍需將自己新增為使用者。

### 症狀：使用者看不到 Experience Cloud 首頁存取 [!UICONTROL Control Panel] 的連結

**原因：**
使用者直到新增為產品設定檔_Campaign-xxx-Administrators/Admin_&#x200B;的使用者後，才能看到連結。

**該做什麼：**
系統管理員需要將使用者新增到他們想要管理的每個執行個體的產品設定檔 _Campaign-xxx-Admins_。 如果使用者是所有執行個體的管理員，則他們仍需將自己新增為使用者。

### 症狀：執行個體未列於 [!UICONTROL Control Panel]

**原因：**
可能是，使用者必須新增為消失的執行個體的使用者產品設定檔_Campaign-xxx-Administrators/Admin_

**該做什麼：**
系統管理員需要將使用者新增到他們想要管理的每個執行個體的產品設定檔 _Campaign-xxx-Admins_。 如果使用者是所有執行個體的管理員，則他們仍需將自己新增為「使用者」。

### 有用的影片

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12&learn=on){transcript=true}

*檢查IMS組織ID （00:26分鐘）*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12&learn=on){transcript=true}

*如何為產品設定檔管理員新增管理員，以便使用[!UICONTROL Control panel] （01:03分鐘）*

### 實用文件

* [探索 [控制面板]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hant)
* [管理[!UICONTROL Control Panel]的許可權](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hant)

## 建立與 SFTP 伺服器（用戶端或 API）的連線

連線至 SFTP 伺服器需要：

* [!UICONTROL Allow listing] 您連接到 SFTP 伺服器的 IP 位址
* 需要以 Adobe Campaign 註冊私人/公有金鑰組
* 如果直接連線到SFTP伺服器，您需要SFTP使用者端軟體

### 實用文件 {#helpful-docs}

* [登入您的 SFTP 伺服器](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hant)

