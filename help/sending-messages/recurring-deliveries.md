---
title: 設定重複、持續的電子郵件行銷活動
description: 瞭解如何設定循環和持續傳遞，並瞭解兩種方法之間的差異。
feature: Workflows, Campaigns
jira: KT-1560
doc-type: feature video
activity: use
team: TM
role: User
level: Beginner
exl-id: 42f2a7e6-7d88-473b-b913-fe09b7016b28
TQID: 'https://experienceleague.adobe.com/JPcr0Ub8i7-L-v9MsR0BKIg0Umc6JuGIX0iBcCAc610'
product_v2:
  - id: dfc56824-e8b9-499e-85d4-21aedb507314
    internal-label: Campaign
  - id: fd6e6e36-54e4-4f1a-96fc-1a750e400d50
    internal-label: Campaign Classic v7
feature_v2:
  - id: a075b2c1-7748-4328-b7f6-343aa314616a
    internal-label: Campaigns
  - id: a658c786-869b-4194-a780-2594d663adda
    internal-label: Data management
subfeature_v2:
  - id: fcb46c0f-76e1-48bc-9dd0-fcf9d97526cf
    internal-label: Workflows
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
level_v2:
  - id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
    internal-label: Beginner
source-git-commit: d4d4654e5b2dee85947373b8dcf139754844b316
workflow-type: tm+mt
source-wordcount: '240'
ht-degree: 50%
---
# 設定重複、持續的電子郵件行銷活動

本教學課程說明如何設定循環和持續傳遞，以及兩種方法之間的差異。

## 循環和持續傳送追蹤 {#recurring-and-continuous-delivery-tracking}

循環和持續傳遞在管理聯絡資料的方式上有所不同：

* **持續傳遞**&#x200B;可讓您將新收件者新增至現有傳遞，並避免每次新增收件者時都必須建立新傳遞。 您可以直接在行銷活動工作流程中更新創意素材，其將會更新傳遞範本「資源」資料夾中的範本。

  持續傳遞會建立「單一」傳遞和傳遞記錄(broadLog)以及追蹤記錄，每次執行傳遞時都會參照新增。

  ![持續傳遞](/help/assets/delivery_continuous.jpg)

* **循環傳遞**&#x200B;每次執行時都會建立新的傳遞執行個體。 例如，如果排程每週執行一次工作流程，則在一年後會產生 52 項傳遞。 這也表示廣泛的記錄檔和追蹤記錄檔會依每個傳送執行個體區隔。

  ![循環傳遞](/help/assets/delivery_recurring.jpg)

## 如何設定循環傳送 {#how-to-set-up-a-recurring-delivery}

此影片說明如何設定循環傳遞和排程器活動。

>[!VIDEO](https://video.tv.adobe.com/v/25040?quality=12&learn=on){transcript=true}

## 如何設定連續傳送 {#how-to-set-up-a-continuous-delivery}

此影片說明如何使用增量查詢來設定持續傳送。

>[!VIDEO](https://video.tv.adobe.com/v/25039?quality=12&learn=on){transcript=true}
