---
lab:
    title: '實驗 2.3： Dynamics 365 Sales 總整實驗'
    module: '模組 2： 學習 Dynamics 365 Sales 的基礎知識'
---

模組 2： 學習 Dynamics 365 Sales 的基礎知識
========================

## 練習實驗 2.3 - Dynamics 365 Sales 總整實驗

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

您是 ABC 公司住宅銷售端的銷售代表。雖然您許多的潛在客戶都來自公司的贊助活動、行銷活動和已購買清單，但您仍然常直接收到客戶的詢價。當您收到這些詢價時，您需要在整個銷售生命週期中手動輸入和處理潛在客戶。 

您最近接到名為 Piper Smith 的來電。由於鄰里最近連續發生竊盜案，因此她想購買一些居家安全設備。您將會把來自 Piper 的潛在客戶資訊輸入系統，嘗試授與其資格，並在完成整個銷售週期。 

在完成實驗後，您將會完成以下事項：

- 在 Dynamics 365 Sales 中輸入潛在客戶

- 授與潛在客戶資格並將其轉換成銷售商機。

- 管理與商機相關的每日活動。 

- 為商機新增報價。 

- 關閉銷售商機。 

- 產生發票。 

## 實驗設定

  - **預估時間**： 30 分鐘

## 指示
  
## 練習 1：在 Dynamics 365 Sales 中建立和授與潛在客戶資格


### 工作 1：建立新的潛在客戶

1. 如有必要，請開啟 InPrivate 瀏覽器並瀏覽至 [Https://home.Dynamics.com](https://home.dynamics.com/) 

2. 出現提示時，請使用講師提供給您的使用者認證來登入。 

3. 從顯示的應用程式清單中，請選取 **Sales Hub。**

4. 使用畫面左側的導覽，選取**潛在客戶**。 

5. 若要檢視系統中目前所有的銷售潛在客戶，請選取**我開啟的潛在客戶**旁的向下箭頭，並從顯示的功能表中選取**現行潛在客戶**。 

6. 若要瀏覽回您的潛在客戶清單，請選取 [現行潛在客戶] 旁的向下箭頭，然後從顯示的功能表中選取**我開啟的潛在客戶**。 

7. 接下來，我們將為 Piper Smith 建立新的潛在客戶，從**我開啟的潛在客戶**檢視表中，選取命令列上的**新增**按鈕。

8. 完成您的新潛在客戶記錄，如下所示：

	- **主題：** 尋找安全設備 –「您的姓名」

	- **名字：** Piper

	- **姓氏：** Smith - 您的姓名縮寫

	- **行動電話：** 888 555-1762

	- **電子郵件：** piper@sample.com


9. 選取命令列上的**儲存**按鈕以儲存新的潛在客戶，並保持潛在客戶畫面開啟。

10. 請注意在記錄頂端的**潛在客戶變商機**商務程序流程。選取 **[授與階段資格]** 以進行選取。完成階段，如下所示：

	- **購買時間範圍：** 本季

	- **預估預算：** 10000 

	- **購買程序：** 個人

	- **識別決策者：** 已完成

11. 選取階段視窗的 **[X]** 來關閉視窗。 

12. 前往畫面中間的記錄 **[時間軸]**，並選取**加號**圖示來新增活動。 

13. 從顯示的功能表中，選取**通話**。

14. 在 [快速建立通話] 畫面上完成通話，如下所示：：

	- **主題：** 尋找居家安全設備

	- **電話號碼：** 888 555-1762

	- **方向：** 撥入

	- **描述：** 在鄰里發生一些案例後，她想要購買安全系統。 

15. 選取**儲存後關閉**按鈕。

16. 請注意**尋找居家安全設備**活動現在已顯示在記錄**時間表**上。請暫留在活動上並選取關閉活動**核取記號圖示**，以將通話標記為已完成。 

17. 在**關閉通話**視窗中，請驗證狀態已設定為**已完成**，然後選取**關閉**按鈕。

 

**重要事項：** 請勿關閉潛在客戶記錄。請保持將其開啟，因為我們會在下個工作中使用它。 

 

### 工作 2：授與潛在客戶成為商機的資格

在拜訪 Piper 之後，您確認她有意進行後續程序，並且我們有可以使她受益的產品和服務。下一步，您將授與潛在客戶記錄資格。這會建立相關的商機記錄，並移至 [潛在客戶變商機] 銷售程序的後續階段。 

1. 在**命令列**上，選取**授與資格**按鈕。 

2. 在系統授與潛在客戶資格後，系統會建立新商機記錄，商務程序會進入**開發**階段。選取**授與資格**階段，以檢視原始潛在客戶記錄。 

3. 選取 **[授與資格]** 階段，以便返回潛在客戶。

4. 選取 **[儲存後關閉]** 按鈕，關閉已建立的潛在客戶記錄。 

 

 

## 練習 2：在 Dynamics 365 Sales 中管理銷售商機

現在我們已成功授與潛在客戶資格成為商機的資格，是逐步執行商機整個生命週期的時候了。

### 工作 1：管理銷售商機並建立報價 

1. 使用畫面左側的導覽，選取**商機**。 

2. 選取 **[我開啟的商機]** 檢視旁的下拉式箭頭，在顯示的功能表中選取 **[所有商機]**。

3. 在命令列上，請選取顯示圖表。請注意，**[最佳客戶]** 圖表會根據 [商機] 資料表來顯示。 

4. 選取 **[最佳客戶]** 旁的下拉式箭頭，在顯示的功能表中選取 **[銷售管道]**。

5. 請選取漏斗圖的 [授與資格] 部分。請注意，商機清單將改為顯示處於授與資格階段的商機。 

6. 選取圖表空白區域中的任何位置，即可再次顯示所有開啟的商機。 

7. 請選取**待完成商機**檢視表旁的下拉箭頭，並從顯示的功能表中選取**我待完成的商機**。**尋找安全設備 - 您的姓名縮寫**可能會是唯一出現的項目，而圖表則會反映出這點。 

8. 在**命令列**上，請選取**隱藏圖表**按鈕。 

9. 請開啟**尋找安全設備 - 您的姓名縮寫**，這是您稍早對潛在客戶授與資格時所建立的記錄。請注意，該記錄已處於**開發**階段，因為它是從之前合格的潛在客戶所建立。  

10. 在記錄頂端**尋找居家安全設備 - 您的姓名縮寫**商機標題上，選取負責人欄位旁的向下箭頭。 

11. 完成填寫下方資料：

	- **預估關閉日期：** 明天

	- **預估營收：** 12,500.00

12. 前往畫面中間的 **[記錄時間軸]**，並選取**加號**圖示來新增活動。 

13. 從顯示的功能表中，請選取**約會**。

14. 在**快速建立上：**

	- **主題：** 快速會議 - 您的姓名縮寫

	- **位置：** 線上

	- **開始時間：** 明天上午 10:00

	- **結束時間：** 明天上午 10:30

15. 在命令列上，請選取**儲存後關閉**

16. 在 [潛在客戶變商機] 商業程序流程中，選取**開發**階段。請注意，您需要識別出利害關係人和競爭者。

17. 選取階段視窗中的 **[X]** 關閉視窗，即可繼續作業。 

18. 在**利害關係人**子格中，注意到 **Piper** 已定義為利害關係人。 

19. 在 [銷售團隊] 子格中，選取**垂直省略符號**。從顯示的功能表中選取**新連線**。 

20. 在 **[搜尋]** 欄位中輸入文字 **「系統」**，然後選取 **[系統管理員]** 記錄。完成後，選取 **[新增]** 按鈕。系統管理員現在應會出現在銷售團隊中。如果沒有，請選取命令列上的**重新整理**按鈕。 

21. 在 [競爭者] 子格中，選取**垂直省略符號**。從顯示的功能表中，選取**新增現有的競爭者**。 

22. 在**查詢記錄**畫面上，選取**新記錄**，然後選取**競爭者**。

23. 在 [快速建立] 中：請在**競爭者**畫面上，將**名稱**欄位設定為 **Coho Security –「您的姓名縮寫」**。

24. 選取**儲存後關閉**按鈕。

25. 確認您剛建立的 Coho Security 記錄為已選取，然後選取 **[新增]** 按鈕。 

26. 在 **「潛在客戶變商機」** 商務程序流程中選取 **[開發]** 階段，可將 **[識別利害關係人]** 和 **[識別競爭者]** 步驟都設為 **[已完成]**。 

27. 選取 **[下一個階段]** 按鈕，前往 **[提案]** 階段。

28. 在**提案**階段中，將**識別銷售團隊**標記為**已完成**。

29. 選取 [提案] 階段上的 **[X]** 來關閉階段視窗。 

30. 在商機記錄上，選取**報價**索引標籤。 

31. 在 [報價] 子格上，選取 **[新增報價]** 按鈕。

 

**重要事項：** 由於這些環境部署了多個第一方應用程式，因此目前已顯示的報價單可能不是銷售相關功能的正確報價單。如果報價名稱**尋找居家安全設備 - 您的姓名縮寫**下方的文字是： **報價。報價**，系統載入正確的表格。如果顯示的是，**報價**如果您需要變更，請選取**報價**旁的下拉式箭頭。從顯示的功能表中，選取**報價**。 

 

### 工作 2：管理報價

現在您有了相關的報價，就需準備好將報價提交給客戶。在正常情況下，我們可能會在將產品交付給客戶之前，將產品新增到報價記錄中。因為我們在共用環境中工作，所以我們將跳過新增報價明細，並逐步解說報價的交付過程。 


1. 您現在需要選取要附加到商機的價目表。  在左側窗格的 **[價目表]** 下方選取搜尋圖示，然後從選項中選取 **[Office 365 USA] (範例)**。在 **[命令列]** 上選取 **[啟用報價]** 按鈕來啟用報價。 

2. 現在報價已建立，讓我們來更新商機記錄以反映新的資料。在 [報價] 記錄上選取 **[尋找安全設備** – **「您的姓名」]** 商機，此項目位在 **[銷售資訊]** 區段下方的 **[商機]** 欄位中。該商機記錄應會在畫面中開啟。 

3. 在 [商機] 記錄上，請選取**提案**階段。 

4. 將 **[開發提案]**、**[完成內部審查]** 和 **[提出提案]** 標示為 **[已完成]**，並選取 **[下一個階段]** 按鈕前往 **[關閉]** 階段。 

5. 在**關閉**階段上，將**完成最終提案**、**提出最終提案**、**傳送感謝函**和**將任務報告歸檔**等步驟標記為**已完成**。 

6. 將**確認決定日期**設為**今天的日期**。 

7. 選取 **[完成]** 按鈕。 

8. 請選取關閉階段視窗上的 **X** 來關閉視窗。 

9. 請選取**報價**索引標籤。 

10. 請開啟**尋找安全設備 - 您的姓名縮寫**報價。 

11. 在**命令列**上，請選取**建立訂單**按鈕。

12. 在建立訂單視窗上，完成填寫以下資料：

	- **狀態原因：** 成交

	- **成交日期：** 今天的日期

	- **關閉商機：** 是

	- **根據報價計算實際營收：** 否

	- **實際營收：** $12,500

13. 請選取**確定**按鈕 

系統會建立與該項目相關的新銷售訂單。此外，系統將關閉報價記錄和相關的商機記錄。一切都完成後，訂單將在您的畫面中開啟。請保持訂單開啟。 

###  

### 工作 3：管理訂單及發票

現在您建立了銷售訂單，我們將關閉訂單並產生發票。在正常情形下，報價記錄中的產品會新增至銷售訂單中。由於我們在共用環境中工作，因此接下來我們會假裝已附加好產品的情況來繼續。 

 

1. 在**命令列**上，請選取**完成訂單**按鈕。 

2. 在 [完成訂單] 畫面上，完成填寫以下資料：

	- **狀態原因：** 完成

	- **完成日期：** 今天的日期

3. 請選取**完成**按鈕。 

4. 在訂單的**命令列**上，請選取**建立發票**按鈕。 

5. 在 **[命令列]** 上選取 **[已付發票]** 按鈕。選取 [確定]。
