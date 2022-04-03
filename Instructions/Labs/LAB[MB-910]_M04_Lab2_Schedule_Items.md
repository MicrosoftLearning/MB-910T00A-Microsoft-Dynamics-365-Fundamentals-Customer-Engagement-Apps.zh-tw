---
lab:
  title: ‘實驗室 4.2：在 Dynamics 365 Field Service 中排程項目
  module: 'Module 4: Learn the Fundamentals of Dynamics 365 Field Service'
ms.openlocfilehash: abbdb5d7f8c2507bebf634a9b0fb1afea8fc8da4
ms.sourcegitcommit: 600ccb76999dbc6fe9f7eaece0c235b0e85706ed
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 01/27/2022
ms.locfileid: "137908817"
---
<a name="module-4-learn-the-fundamentals-of-dynamics-365-field-service"></a>課程模組 4：學習 Dynamics 365 Field Service 的基本概念
========================

## <a name="practice-lab-42---schedule-items-in-dynamics-365-field-service"></a>練習實驗 4.2 - 在 Dynamics 365 Field Service 中排程項目

## <a name="lab-setup"></a>實驗設定

  - **預估時間**：20 分鐘

  **注意：** Internet Explorer 無法開啟 [預約需求] 窗格。 請使用 Microsoft Edge 或 Google Chrome 來完成此練習。
  
## <a name="instructions"></a>指示

1. 如尚未開啟，請先開啟 **Dynamics 365 Field Service** 應用程式。 

2. 使用左側的導覽，選取 [資源] 區域，然後選取 [資源]。

3. 在 [命令列] 上選取 [新增] 按鈕，以便建立新的可預約資源。

    - **資源類型：** 。連絡資訊

    - **連絡人：** Eleanor Ribeiro

4. 在 [命令列] 上選取 [儲存後關閉] 按鈕。

5. 重複以上步驟，多建立三個可預約資源。

    - **資源類型：** 。連絡資訊

    - **連絡人：** Abbie Gardiner


    - **資源類型：** 。連絡資訊

    - **連絡人：** Aidan Knaggs
    
    - 選取 [相關] 索引標籤並新增「相關地區 - WA」


    - **資源類型：** 。連絡資訊

    - **連絡人：** Cacilia Viera
    
    - 選取 [相關] 索引標籤並新增「相關地區 - WA」


6. 在 [命令列] 上選取 [儲存後關閉] 按鈕。

27 使用左側的導覽，選取 [服務] 區域，然後選取 [工單]。

8. 在 [命令列] 上選取 [新增] 按鈕，以便建立新工單。

9. 完成工單詳細資料，如下所示：

    - **服務帳戶：** Adatum Corporation

    - **工單類型：** 服務

    - **價目表：** CRM 服務 USA (範例)

    - **應課稅：** 否

10. 選取 [儲存]，以便儲存變更。\

    - **主要事件類型：** 單元過熱。 (建立新項目)

11. 在 [工單] 的 [命令列] 上選取 [預約] 按鈕。 這將開啟 **排程小幫手。** 

12. 系統應會顯示排程該項目的選項。 選取 [Abbie Gardiner] 記錄。

13. 在 **建立資源預約** 視窗中，將 **開始時間** 設為下一小時。

14. 將 **結束時間** 設為之後的 **2.5 小時**。 

15. 選取 [預約 &amp; 結束] 按鈕，以預約項目並離開排程視窗。 

16. 回到 [工單] 之後，選取 [命令列] 中的 [儲存後關閉] 按鈕。 

17. 使用左側的導覽，選取 [工單]。 選取 [未排程的工單] 檢視。

18. 畫面的底部為 [預約需求] 面板。 請使用面板頂端中間的控點開啟面板。 選取 [未排程的工單] 索引標籤。

19. 利用您寫下的工單編號，選取您之前建立的 [Adventure Works] 工單。 從顯示的選項中選取 [尋找可用性]。 

20. 這將開啟 **排程小幫手。** 

21. 系統應會顯示排程該項目的選項。 選取 [Aidan Knaggs] 記錄。

22. 在 **建立資源預約** 視窗中，將 **開始時間** 設為下一小時。

23. 將 **結束時間** 設為之後的 **2.5 小時**。 

24. 選取 [預約 &amp; 結束] 按鈕，以預約項目並離開排程視窗。 

25. 有時候，您可能需要根據技術人員的時段衝突或其他項目來重新排程工單。 這可透過分派人員利用排程面板來輕鬆完成。 

26. 選取排程面板 (位在資源名稱欄上方) 上的搜尋資源方塊，輸入「Abboe」，並找到今天稍後為 Abbie 排程的工單。 

27. 以右鍵按一下工單，從顯示的功能表中選取 [替代資源]，然後選取 [尋找替代] 按鈕 **。**
