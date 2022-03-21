# University-Topic-EAP
大學專題-活動協助解決平台(Event Assistance Platform)

## 實作目的
台灣每年發生許多天災，<br>
普遍民眾對災害平台的認真與使用性低，<br>
許多公益活動並沒有管道可以宣傳活動與募資，<br>
也沒有一個統一的管道能讓公益活動進行後續的追蹤，<br>
因而研究探討該解決方案內容。

## 設計理念與技術
主要使用C# ASP.NET MVC的網頁應用程式來製作專案，<br>
利用推文的方式，將平台劃分成提案者與參與者兩方，<br>
提案者可將自己想要解決的問題，藉由平台將問題提出，<br>
讓有興趣的參與者能夠加入共同討論解決難題。<br>
再搭配上類似RPG的虛擬角色與經驗升級互動等方式，<br>
進行頻繁的互動，讓大家能夠多使用這個平台，進而達到資訊即時分享與解決的目的。<br>
- C# ASP.NET MVC Framework
- ADO.NET
- SQL Server(MSSQL)
- HTML+CSS
- Bootstrap CSS Framework
- JavaScript+jQuery
- Three.js

## 主要實作功能
實作功能包含完整的活動參與流程，除了CRUD增刪改查等動作之外，<br>
也實際做出了3D的RPG角色系統機制，並且能夠讓使用者觀看彼此的3D虛擬角色。<br>
還有包括許多詳細的網頁功能。<br>
- 詳細提案活動參與流程 (尋找提案->查詢提案->參與活動->返回提案頁面->選擇實體行動支持或是經濟支持->顯示參與活動回條)
- 佈告欄提案活動顯示(包含分頁系統)
- 上傳提案活動圖片
- 參與排行榜系統
- 提案活動標籤TAG(食、衣、住、行、育、樂)
- 搜尋提案活動(模糊搜尋、標籤TAG分類)
- 會員登入與註冊系統
- 提案活動狀態變更
- 提案活動獎懲機制(預防惡意結束提案等內容)
- 提案活動參與名單簽到與查詢列印功能
- 提案活動當前進度查詢(募資、人力)
- 個人創建或參與的提案活動查詢
- 個人3D虛擬角色商店與展示功能

## 相關程式畫面
### 登入註冊<br>
<img src="https://github.com/lfre84216/BookBorrowSystem/blob/main/7.png">
<img src="https://github.com/lfre84216/BookBorrowSystem/blob/main/8.png">
<br>

### 使用者介面<br>
<img src="https://github.com/lfre84216/BookBorrowSystem/blob/main/1.png">
<img src="https://github.com/lfre84216/BookBorrowSystem/blob/main/2.png">
<img src="https://github.com/lfre84216/BookBorrowSystem/blob/main/3.png">
<img src="https://github.com/lfre84216/BookBorrowSystem/blob/main/4.png">
<br>

### 管理者介面<br>
<img src="https://github.com/lfre84216/BookBorrowSystem/blob/main/5.png">
<img src="https://github.com/lfre84216/BookBorrowSystem/blob/main/6.png">
<br>

## 製作過程與困難點
在實作該專案的過程中，有嘗試想要實際讓資料庫可以被外部來連接，<br>
達成實際直接遠端資料庫的功能，<br>
所以在網路這方面有另外研究了關於虛擬伺服器的功能，<br>
讓實作出來的程式也能透過外部裝置來進行連線。
