---
lab:
    title: '實驗 5.3： Dynamics 365 Project Operations 總整實驗'
    module: '模組 5： 學習 Dynamics 365 Project Operations 的基礎知識'
---

模組 5： 學習 Dynamics 365 Project Operations 的基礎知識
========================

## 練習實驗 5.3 - Dynamics 365 Project Operations 總整實驗

## 實驗情境

ABC 公司專門從事安全設備的製造、銷售、安裝和服務。他們的產品包含室內和室外監控攝影機、濕度和火災感應器、監控服務等項目。 

ABC 公司使用 Dynamics 365 應用程式，與其組織不同區域的所有客戶進行從銷售到服務的互動。 

**銷售和行銷**

ABC 公司透過鎖定目標的行銷活動，直接向住宅客戶行銷。該公司根據客戶所在的城市和其他因素來鎖定目標。行銷素材會透過電子郵件傳送，並根據他們與電子郵件的互動進行相應引導。 

雖然他們有些較小型產品會透過零售商售出，但大多數產品是由內部銷售人員直接售出給客戶。

在內部，他們將焦點放在兩個關鍵區域： 

- **住宅客戶：** 住宅客戶通常正在尋找個別元件，或要購買整個居家解決方案。這些銷售週期一般而言較短，來自社群媒體、網站、推薦或來自潛在客戶的直接連絡。由於住宅客戶通常更關注特定產品或較小型的安裝項目，因此他們的銷售週期通常會持續幾天或幾週。 

- **企業客戶：** 企業賣方將焦點放在需要更專業且能量身打造商務解決方案的客戶上。企業銷售通常透過連結溝通跨越多個位置，而且往往需要多重資源以完成專案。這些銷售週期通常更長，並且有更多移動零件。 

重要的是，ABC 公司的所有賣方在向客戶銷售產品時，無論他們專注於哪個區域，都擁有必要的工具、資源和指引。 

**系統安裝：**

對於購買的安全設備，安裝程序會因所售出之客戶類型而有所不同。 

- **住宅客戶：** 由於住宅安裝通常僅需要不到一天的時間，因此會由內部員工來完成。銷售完成後，系統會建立工單並排程識別的合格技術人員執行安裝。 

- **企業客戶：** 企業部署可能需要數個月時間，並需要專案經理來監督每日作業。這包含建立專案計劃、定義專案團隊和排程資源。 

**服務與支援：**

一旦安裝好系統後，ABC 公司便會提供售後支援。如果客戶有問題，他們則可以連絡客戶支援。有名專員嘗試要與客戶遠端合作來解決他們的問題。如果無法遠端解決他們的問題，支援專員則可以將問題向上呈報至工單，並由合格的現場技術人員加以排程和處理。 
## 目標

ABC 公司的企業賣方會將其注意力放在需要更專業且能量身打造安全性商務解決方案的客戶上。有鑑於此原因，企業銷售通常透過連結溝通跨越多個位置，而且往往需要多重資源以完成專案。ABC 公司的企業銷售週期會花上好幾個月，而且需要多個移動零件來執行。 

一旦公司將系統售出給企業客戶，就要花數個月來實作專案。每項專案會指派給監督專案規劃和日常營運的專案經理。這包含建立專案計劃、定義專案團隊和排程資源。 

身為企業賣方，您負責將高端自訂安全性解決方案銷售給客戶。您最近接到 Consolidated Sample 公司的來電。他們希望有完全的整合式安全性解決方案能延伸至其所有據點。您要 Consolidated Sample 的潛在客戶輸入系統，將他們引入專案銷售週期中並建立對應專案。 

在完成實驗後，您將會完成以下事項：

- 管理與專案商機相關的日常活動。 

- 新建和定義專案報價。 

- 產生專案合約。 

- 建立專案並定義專案團隊。 

## 實驗設定

  - **預估時間**： 45 分鐘

## 指示

## 練習 1：建立專案報價和專案預估

「專案商機」會用來擷取關於潛在專案的整體詳細資料。當有越來越多關於專案的詳細資料出現時，您就可以建立「專案報價」。專案報價通常包含與不同角色、時間表和定價相關的詳細資料。專案報價是向客戶展示的內容。此外，您也可以在其中開始建立與您銷售專案相關的專案計劃。這會在專案售出後節省時間，因為系統已擷取許多與專案相關的詳細資料。

在此練習中，您將建立專案並定義與專案報價相關的詳細資料。 

### 工作 1：建立專案報價。  

1. 在開啟 [專案商機] 的情況下，請選取**報價**索引標籤。 

2. 在 [報價] 子格中，選取 **[新增報價]** 按鈕。

3. 在新的報價記錄開啟後，將報價中的 **[產品價目表]** 欄位設為 **[美國帳單費率]**。 

4. 請選取**報價明細**索引標籤。

5. 選取並開啟**系統實作**明細項目。 

6. 在**專案**欄位中，選取**新專案。** 

7. 在**快速建立專案**畫面上，完成專案如下：

	- **名稱：** 完成全域實作 – 您的姓名縮寫

	- **專案經理：** 選取您的使用者記錄

	- **行事曆範本：** 預設工作範本

	- **合約單位：** Fabrikam US

	- **預估開始日期：** 從今天起一週

	- **預估人力成本：** $ 175,000

	- **預估開支成本：** $ 50,000

	- **預估總成本：** $ 225,000

8. 選取**儲存後關閉**按鈕。

9. 下一步，我們將定義是否可以針對指派給專案的特定角色收費。選取**收費角色**索引標籤。

10. 選取後開啟**機器人工程師**角色，並設定 [不應收費] 的計費類型。

11. 在**命令列**上，選取**儲存後關閉**按鈕。

12. 選取**報價明細詳細資料**索引標籤。

13. 在子格上，選取**新增報價明細詳細資料**按鈕。

14. 完成**報價明細詳細資料**項目，如下所示：

	- **描述：** 通訊線路運作 – 您的姓名縮寫

	- **交易類別：** 時間

	- **角色：** 網路技術人員

	- **類別：** 時間

	- **開始日期：** 從今天起一個月

	- **結束日期：** 從今天起兩個月

	- **資源分配單位：** Fabrikam US

	- **單位：** 小時


15. 選取**儲存後關閉**按鈕，以關閉明細詳細資料項目。 

16. 在**命令列**上，選取**儲存後關閉**按鈕。 


**注意：** 保留 [專案報價] 開啟，以在下個工作中使用。 


### 工作 2：關閉專案報價並建立 [專案合約]。

在此工作中，您將關閉建立的專案報價，並將其轉換成專案合約。執行專案時，可使用並利用專案合約。 


1. 在開啟**完成全域安全性實作 – 您的姓名縮寫**專案報價記錄的情況下，選取命令列上的**以成交關閉**按鈕。 

2. 在**您確定要關閉報價**畫面上，選取**確定**。

3. 一旦關閉報價，新建的**完成全域安全性實作 – 您的姓名縮寫**專案合約隨即顯示。 

 

**注意：** 保留 [專案合約] 開啟，以在下個工作中使用。 

## 練習 2：管理專案

利用 Project Operations 的其中一項專案銷售功能優點，就是能在銷售處理期間建立專案。建立的專案將從不同的銷售相關記錄 (例如專案報價和專案合約) 存取。 

在此練習中，您將管理一些與專案相關的初始工作，例如定義專案詳細資料、定義專案團隊和概述專案工作。 


### 工作 1：管理基本的專案資料。 

1. 在**完成全域安全性實作 - 您的姓名縮寫**專案合約開放的情況下，選取**相關**索引標籤。 

2. 從顯示的功能表中，選取**專案。**

3. 開啟**全域安全性實作 – 您的姓名縮寫**專案。 

4. 在**專案服務**商務程序流程上，選取**新**階段，然後選取**下一個階段**按鈕以進入**報價**階段。 

5. 在**報價**階段中，將**預計完成日期**欄位設為**從今天起六個月**。 

6. 選取**下一個階段**按鈕以進入**計劃**階段。 

 
### 工作 2：建立專案團隊。

每項專案將有一組成員協助執行該專案。在此工作中，我們將定義組成專案團隊成員的資源。 

 
1. 在**完成全域安全性實作 – 您的姓名縮寫**專案記錄開啟的情況下，選取**團隊**索引標籤

2. 在**所有團隊成員**子格上，選取 **+ 新增**按鈕。

3. 設定團隊成員記錄，如下所示：

	- **職位名稱：** 機器人工程師 – 您的姓名縮寫

	- **可預約資源：** Allison Dickson

	- **角色：** 機器人工程師

4. 選取 [儲存後關閉] 按鈕旁的箭頭。從顯示的功能表中，選取**儲存後新建。**

5. 設定下個團隊成員記錄，如下所示：

	- **職位名稱：** 軟體工程師 – 您的姓名縮寫

	- **可預約資源：** Bob Kozak

	- **角色：** 軟體工程師

6. 選取 [儲存後關閉] 按鈕旁的箭頭。從顯示的功能表中，選取**儲存後新建。**

7. 設定團隊成員記錄，如下所示：

	- **職位名稱：** 網路工程師 – 您的姓名縮寫

	- **可預約資源：** Dianna Woodward

	- **角色：** 網路技術人員

8. 選取**儲存後關閉**按鈕。


### 工作 3：定義 [專案排程]。

定義專案的另一個重要部分是，為專案定義專案工作和排程。在此工作中，我們增加一些專案工作並且將它們與不同角色產生關聯。 


1. 開啟**完成全域安全性實作 – 您的姓名縮寫**專案，選取**排程**索引標籤。 

2. 在排程子格中的工具列上，選取 **+ 新增**按鈕。 

3. 在顯示列中，將**名稱**欄位設為**系統開發**。

4. 在排程子格中的工具列上，再次選取 **+ 新增**按鈕以新增至其他項目。 

5. 設定項目，如下所示：

	- **名稱：** 建立系統配置

	- **投入量：** 25

6. 在排程子格中的工具列上，選取 **+ 新增按鈕**以新增至其他工作。 

7. 設定項目，如下所示：

	- **名稱：** 設計攝影機

	- **前置作業：** 建立系統配置

	- **投入量：** 50

8. 在排程子格中的工具列上，再次選取**加號 (+) 新增按鈕**以新增至最後工作。 

9. 設定項目，如下所示：

	- **名稱：** 驗證並核准設計

	- **前置作業：** 設計攝影機

	- 投入量：8 

 
**注意：** 停留在排程索引標籤，因為我們將在下個工作中做一些額外修改。 


### 工作 4：將資源與專案建立關聯。

作為定義專案排程的一部分，您可以指定將用來滿足人員需求的資源類型。這些可以是實際具名資源，或未來具名資源取代的一般資源。在此工作中，您將為建立的專案工作定義具名和一般資源。 

1. 如有必要，請開啟**完成全域安全性實作 – 您的姓名縮寫**專案，並選取**排程**索引標籤。 

2. 在 **[資源]** 欄位中找到並選取您之前新增的 **[建立系統配置]** 工作。 

3. 從顯示的功能表中，選取**建立**。 

4. 設定專案團隊成員，如下所示

	- **職位名稱：** 一般機器人工程師 – 您的姓名縮寫

	- **可預約資源：** 一般資源

	- **角色：** 機器人工程師

5. 選取**儲存後關閉**按鈕。 

6. 驗證已新增至 [資源] 欄位的**一般機器人工程師 – 您的姓名縮寫**資源。 

7. 找出**設計相機**工作並選取**資源**欄位。 

8. 從顯示的功能表中，選取**建立**。 

9. 設定專案團隊成員，如下所示：

	- **職位名稱：** 一般機器人工程師 – 您的姓名縮寫

	- **可預約資源：** 一般資源

	- **角色：** 機器人工程師

10. 選取**儲存後關閉**按鈕。 

11. 找出**驗證並核准設計**的工作後，選取**資源**欄位。 

12. 從顯示的功能表中，選取 **Allison Dickson**。 


恭喜，您在 Dynamics 365 Project Operations 中已成功售出並建立專案。在此處，專案經理可以管理不同外觀的專案，例如排程資源、監控專案排程，以及管理時間和開支。 

 

 