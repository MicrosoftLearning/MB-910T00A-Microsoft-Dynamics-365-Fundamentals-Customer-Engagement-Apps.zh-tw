---
lab:
  title: ‘實驗室 4.2：在 Dynamics 365 Field Service 中排程項目
  module: 'Module 4: Learn the Fundamentals of Dynamics 365 Field Service'
ms.openlocfilehash: ca0728e865cf16478ab84f160cf34538e521c91e
ms.sourcegitcommit: 6065e6a662bd0407d37fcc565c1b2da1c916255d
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/29/2022
ms.locfileid: "144404993"
---
<a name="module-4-learn-the-fundamentals-of-dynamics-365-field-service"></a>課程模組 4：學習 Dynamics 365 Field Service 的基本概念
========================

## <a name="practice-lab-42---schedule-items-in-dynamics-365-field-service"></a>練習實驗 4.2 - 在 Dynamics 365 Field Service 中排程項目

## <a name="lab-setup"></a>實驗設定

  - **預估時間**：20 分鐘

  **注意：** Internet Explorer 無法開啟 [預約需求] 窗格。 請使用 Microsoft Edge 或 Google Chrome 來完成此練習。
  
## <a name="instructions"></a>指示

1.  如尚未開啟，請先開啟 **Dynamics 365 Field Service** 應用程式。  

2.  使用左側的瀏覽介面，選取 **工單**。

3.  在 [命令列] 上選取 [新增] 按鈕，以便建立新工單。

4.  完成工單詳細資料，如下所示：
    - 服務帳戶：ADatum Corporation
    - 主要事件類型：MRI 掃描儀離線
    - 應課稅： 否
    
5.  選取 **儲存後關閉**，以儲存您的變更並結束新的工單。

6.  在 [工單] 的 [命令列] 上選取 [預約] 按鈕。  這將開啟 **排程小幫手**。  

7.  系統應會顯示排程該項目的選項。  選取 **Ryan Brim** 記錄。

8.  在 [建立資源預約] 視窗中，將 [開始時間] 設為 [下一小時]。

9.  將 **結束時間** 設為之後的 2.5 小時。  

10. 選取 [預約並結束] 按鈕，以預約項目並離開排程視窗。  

11. 回到工單後，請按一下 **命令列** 的 [儲存後關閉] 按鈕。  

12. 使用左側的導覽，選取 **排程面板**。

13. 在需求面板中的畫面底部，選取 **未排程的工單**。

14. 利用您寫下的工單編號，選取您之前建立的 [Adventure Works] 工單。 從顯示的選項中選取 [尋找可用性]。  

15. 這將開啟 **排程小幫手**。  

16. 系統應會顯示排程該項目的選項。  選取 Bob Kozak 記錄。

17. 在 [建立資源預約] 視窗中，將 [開始時間] 設為 [下一小時]。

18. 將 **結束時間** 設為之後的 2.5 小時。
  
19. 選取 [預約並結束] 按鈕，以預約項目並離開排程視窗。 

20. 有時候，您可能需要根據技術人員的時段衝突或其他項目來重新排程工單。  這可透過分派人員利用排程面板來輕鬆完成。  

21. 按一下排程面板 (位於資源名稱欄的正上方) 上的 [搜尋資源] 方塊，輸入 Ryan 並找出今天稍後為 Ryan 排程的工單。  

22. 以右鍵按一下工單，從顯示的功能表中選取 [替代資源]，然後選取 [尋找替代] 按鈕。


