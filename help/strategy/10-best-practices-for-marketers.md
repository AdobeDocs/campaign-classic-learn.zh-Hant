---
title: Adobe Campaign 成功行銷的十大最佳實務
description: 了解十大最佳實務，協助 Adobe Campaign 從業人員充分發揮並加速消費者數位轉型，並向客戶提供更佳體驗。
doc-type: article
feature: Personalization, Campaigns, Subscriptions, Deliverability
role: User
level: Beginner
jira: KT-11772
last-substantial-update: 2023-01-31T00:00:00Z
exl-id: 7152c09f-7ea0-49a8-ac3b-cc304d42c7e4
source-git-commit: eae208987b8430773421cba7aec2f77d5441b618
workflow-type: tm+mt
source-wordcount: '1265'
ht-degree: 99%

---

# [!DNL Adobe Campaign] 成功行銷的十大最佳實務

Christian Klimczyk 自稱為「Adobe 控」，擁有 7 年的 [!DNL Adobe Experience Cloud] 專業知識，主要側重於 [!DNL Adobe Campaign]。Christian 及其團隊以大型 CPG 公司的 Adobe 平台所有者身分，利用 [!DNL Campaign] 跟所有消費者通訊及互動。 他們可跨直接郵件、電子郵件與簡訊/MMS 來協調及管理高法規要求與多頻道消費者行銷活動，順暢無阻。

Christian 在本文分享自己的最佳實務，以便幫助 Adobe Campaign 從業人員充分發揮及加速消費者數位轉型，並為客戶提供更佳體驗。


## 1. 形成整體的統籌行銷與傳遞計畫

確保您成功執行 [!DNL Adobe Campaign] 的第一步是了解您的工具與客戶期望，而這點不論對任何類型的行銷而言均成立。 清楚定義並了解您聯絡消費者的頻道，了解何時及為何使用該頻道。

Adobe Campaign 是一項彈性工具，可讓您以多種方式執行及協調通訊。 [在每次購買歷程，五成客戶會採用三到五種頻道](https://www.mckinsey.com/capabilities/operations/our-insights/redefine-the-omnichannel-approach-focus-on-what-truly-matters)。因此，了解並事先規劃如何使用這些頻道，對於實現平台的全部潛力並與客戶產生共鳴至關重要。

## 2. 記錄並了解客戶資料

<!-- Sandra, this paragraph opens as if it's going to discuss the advantages of segmentation, but it left me hanging. So, I hit the Hubspot link and dug into it a bit, and it seemed to me like the juicy information is this quote: 

"A study by Hubspot revealed that 30% of the marketers who participated in it used market segmentation techniques to improve email engagement. Segmented campaigns had 14.31% higher open rates and saw 101% more clicks than non-segmented campaigns.

"Email marketers who segmented their audience before campaigning stated that the revenue generated increased to up to 760%. Targeted and segmented emails bring in 58% of all revenue." [Link](https://www.notifyvisitors.com/blog/segmentation-statistics/) 

I added that second paragraph about 760% revenue and broke up the rest of the section, touched it up to help make the Hubspot example a little more impactful. If I altered this section too much, you can reject the change. It didn't have mistakes, but it felt like it didn't tie the segment example strongly enough to the point about data design. See if this is okay...-->

根據 [Hubspot 研究](https://www.linkedin.com/pulse/customer-segmentation-effective-b2b-business-industry-sabreen)，與非細分行銷活動相比，細分行銷活動的開放率可提高14.31%，而點擊次數可增加 101%。 電子郵件行銷人員指出若在行銷活動之前細分客群，產生的收入可增加高達 760%。

您可在 Adobe Campaign 快速輕鬆規劃細分。 然而，為簡化並促進流程，行銷活動營運商與行銷從業人員在設計及要求建立並執行行銷活動時，必須對其基礎資料具書面了解。 跟支援您[!DNL Campaign]執行個體的管理員與開發人員合作時，請務必了解您目前的資料，以及如何預測可能需要的資料。

支援行銷活動的基礎資料結構是否完備決定了您行銷活動的成果。 在整合平台或跳至消費者資料平台時，若發生問題，了解並記錄此資料結構也會有所幫助

## 3. 規劃行銷活動的時間

跟您的顧客一樣，您每天都有例行活動。 行銷活動的傳送及協調應符合此節奏。 否則，您可能無法聯絡客戶，因為 [85% 的已傳送郵件未開啟，而 98%的已傳送郵件未獲點進](https://www.validity.com/resource-center/state-of-email-2021/)。

例如，如果客戶早上利用手機查看最佳交易，您可考慮傳送行銷活動簡訊給他們。 如果他們在晚上瀏覽下個熱門趨勢，請考慮傳送後續電子郵件，內含免運費促銷代碼。 同樣重要的是，利用 [!DNL Campaign] 的熱度圖工具來追蹤工作流程與傳送的執行時間。 協調及促進跨多個品牌的通訊可能是一項挑戰。 對於訊息與行銷活動執行個體的整體穩定性及力量而言，[密切關注並了解電子郵件的節奏、步調與時間](https://experienceleaguecommunities.adobe.com/t5/adobe-campaign-classic-blogs/predictive-send-time-optimization-with-adobe-campaign/ba-p/561554)重要性不可小覷。

## 4.在需要個人化的地方使用

如今，消費者期望收到一定程度個人化的訊息。 [80% 的客戶較可能從提供個人化體驗的品牌購物](https://us.epsilon.com/power-of-me)。主旨使用其名字是個好點子。 不過，個人化可更進一步。 您可納入其瀏覽過的產品、將其與連結至類似產品，或繼續強化您品牌的整體體驗與外觀感受。 每項做法均有其成效，並能推動訊息的參與度及點開率。

## 5. 有健全的創意資產清單 Assets

創意資產 Assets 是火車頭，協助您推動有效且良好運作的行銷活動。 隨著成功接觸消費者，您的行銷流程也跟著擴展及成熟，而您也需要更豐富的創意內容。 消費者對此有所期待。

您團隊可設定的下一筆傳送速度決定了您的進展速度。 這通常需要新穎而令人興奮的內容。 [!DNL Adobe Campaign] 讓設定範本以及接收與準備傳送變得簡單。 然而，擁有健全的創意素材管道極為重要，因為根據 [Litmus 報告](https://www.litmus.com/resources/state-of-email/)，58% 的行銷人員指出，建立單一電子郵件行銷活動需要兩週或更久的時間。

## 6. 了解並管理訂閱與偏好設定

管理及維護訂閱偏好設定可能會迅速變得令人困惑，導致各種層級的風險。 例如，透過客戶不會回應的頻道向其傳送錯誤訊息，九成消費者表示，負面體驗會降低其未來購買該品牌的可能性。 從更大的規模來看，您可能會面臨法規與合規風險以及罰款。

透過使用專業的[!DNL Adobe Campaign]與其他行銷技術工具，您可預先制定策略以管理選擇加入項目並耕耘這個不斷發展的生態系統。 這通常是最大的行銷活動成功量度之一，因此，隨著行銷活動策略的發展及成熟，周密的規劃會帶來寶貴的回報。

## 7. 了解並規劃傳遞能力

_傳遞能力_&#x200B;通常看似是神秘而複雜的概念。 傳遞能力的重要基本規則是策略規劃。 準備 IP 位址並建立良好聲譽需要時間。 聲譽可能在短時間內下降，導致修復任何已發生的損害成為一大挑戰。 事實上， **六分之一的電子郵件無法到達收件匣**。

傳遞能力問題可能肇因於多種因素：技術因素或根據消費者對行銷回應方式而產生的問題。 在建立並執行行銷活動以及在回顧流程時，把[傳遞能力](https://business.adobe.com/tw/products/campaign/email-deliverability.html)謹記在心可確保您維持健康且穩定的環境，並持續向客戶提供正面體驗。

## 8. 規劃並制定行銷活動回顧流程

儘管您忙於行銷活動的傳遞及協調，但檢閱您已完成的工作並重新評估行銷活動的流程與細分，常會發揮同樣或甚至更大的效果。 根據行銷活動執行的規模與速度，每兩到四週回顧一次行銷活動。

建立一組範本問題有助進行深入且深思熟慮的對話，主題可涵蓋如何改善行銷活動前置時間、創造性或細分市場等等。 有時僅能從先前執行的活動汲取經驗，改善並加快速度。

## 9. 測試並重覆

當嘗試新事物時，未必能一次就取得成功。 因此，測試並重覆流程與策略非常重要。 在一組可能希望不大或可能是很合適的客戶對象上試試。 切換創意內容。 嘗試新號召用語。為改變而改變往往效果不彰，但若進行許多小型而精確的實驗，長時間下來可能為您與客戶積累出未來巨大的勝利。

## 10. 盡可能敏捷

市場持續變化，並以越來越快的速度前進。 鼓勵您的行銷活動團隊盡可能保持輕快敏捷，這對保持競爭力並繼續滿足不斷提高的客戶期望至關重要。

[35% 的數位行銷領導者認為，最大的挑戰來自組織內部](https://www.gartner.com/en/newsroom/press-releases/gartner-says-35--of-digital-marketing-leaders-believe-the-bigges)。為達此目的，請跨幾個平台進行交叉訓練，增進您對資料流程、結構或其他 Adobe 解決方案的了解，並為行銷活動建立應變計畫。 這種思維模式可透過多種方式實現，但若要實現短期與長期成功，對敏捷與規劃的總體承諾不可或缺。
