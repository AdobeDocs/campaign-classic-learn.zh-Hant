---
title: 如何在Adobe Campaign Classic中設定驗證工作流程
description: 瞭解如何設定不同的核准驗證工作流程。
feature: Workflows, Approvals
jira: KT-1566
doc-type: feature video
activity: setup
team: TM
role: User
level: Experienced
exl-id: 34fbb91d-ae99-497c-872e-55ce2e6ea2aa
source-git-commit: 35e036486c5b533b54b3f626d88734e9a9fc3b8a
workflow-type: tm+mt
source-wordcount: '262'
ht-degree: 96%

---


# 建立驗證工作流程

Adobe Campaign 提供數個選項，供行銷人員檢閱及提供傳遞內容、行銷活動目標、資料擷取和預算核准。

本教學課程說明如何設定不同的核准驗證工作流程。

## 先決條件 {#prerequisite}

在啟用核准步驟之前，行銷團隊必須定義個別審核者：

* 核准活動中的 Adobe Campaign 審核者角色可以是單一審核者 (操作員) 或一組審核者 (操作員角色)。
* 若要讓行銷活動開發人員將審核者選為行銷活動或傳送中的核准者，審核者和審核者群組必須由管理員在 Adobe Campaign 中設定。

## 設定行銷活動的核准   {#configuring-approvals-for-campaigns}

如果您的行銷活動工作流程中的所有傳遞都有相同的審核者集，請在行銷活動層級設定核准和審核者，以套用行銷活動核准功能。 執行工作流程後，核准工作和審核者會下推至工作流程的每個傳遞活動。

>[!VIDEO](https://video.tv.adobe.com/v/25175?quality=12&learn=on){transcript=true}

## 設定用於傳送的核准   {#configuring-approvals-for-deliveries}

您也可以在傳遞層級設定核准。 如果傳遞核准步驟及審核者與行銷活動核准步驟及審核者有所不同，則傳遞設定會覆寫行銷活動設定。

>[!VIDEO](https://video.tv.adobe.com/v/25176?quality=12&learn=on){transcript=true}

## 設定核准活動  {#configuring-an-approval-activity}

與傳遞或行銷活動核准不同，核准活動可讓使用者在工作流程中建立核准流程。 如此一來，即可在傳遞啟動前核准目標定位選擇邏輯。 如有需要，也可在工作流程中的多個層級進行核准。

>[!VIDEO](https://video.tv.adobe.com/v/25174?quality=12&learn=on){transcript=true}

如需詳細資訊，請參閱[核准文件](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html?lang=zh-Hant)
