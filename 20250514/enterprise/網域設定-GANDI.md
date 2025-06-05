---
title: "網域設定-GANDI"
last_modified: "2024-08-28"
categories: [TW台灣站,網站設定>網域設定,常見問題]
tags: []
permalink: "https://www.cyberbiz.io/support/?p=13235"
---

![](https://www.cyberbiz.io/support/wp-content/uploads/適用站別.png)
[![](https://www.cyberbiz.io/support/wp-content/uploads/台灣站.png)](https://www.cyberbiz.io/support/?page_id=2490)
**功能說明：**  

* 在 Gandi 購買網域，進行轉址操作。
* 在Gandi.net後台DNS設定，設定CNAME，將網址連到您在 CYBERBIZ 建立的網站使用。 
* 若希望沒有www的網域也可以連到網站，請設定 轉址。 
* [DNS 設定錯誤訊息解決方式](https://www.cyberbiz.io/support/wp-content/uploads/網域設定-GANDI11.png)
**操作目錄：**

* 設定 DNS 紀錄
* 轉址設定
* CYBERBIZ 轉址設定
注意事項:  

* 完成或異動DNS代管設定，約24小時內生效 (約1小時之後，就可以在網站後填入網域) 
* 可至 [DNSCHECKER](https://dnschecker.org/#CNAME/) 確認網頁是否轉址成功。 
* 若有其他網域設定 請至 [Gandi後台](https://help.gandi.net/zh-hans/contact) 詢問 

📌 設定 DNS 紀錄  

1. 進入 [Gandi 後台](https://www.gandi.net/zh-Hant)，點選左側「域名」。  
[![網域設定-GANDI01](https://www.cyberbiz.io/support/wp-content/uploads/網域設定-GANDI01.png)](https://www.cyberbiz.io/support/wp-content/uploads/網域設定-GANDI01.png)



2. 點選下方貴司購買的網域。  
[![網域設定-GANDI02](https://www.cyberbiz.io/support/wp-content/uploads/網域設定-GANDI02.png)](https://www.cyberbiz.io/support/wp-content/uploads/網域設定-GANDI02.png)



3. 點選「DNS 紀錄」，並按下「新增紀錄」。  
[![網域設定-GANDI03](https://www.cyberbiz.io/support/wp-content/uploads/網域設定-GANDI03.png)](https://www.cyberbiz.io/support/wp-content/uploads/網域設定-GANDI03.png)



4. 設定 新增DNS紀錄，完成後點選「建立」  
【類型】: CNAME  
【TTL(暫存時間)】: 10800  
【單位】: 秒  
【名稱】: 輸入www  
【主機名稱】: 您在 CYBERBIZ的網域。(例 : xxx.cyberbiz.co. )  
*紀錄的主機名稱最後一定要加上一點 (「.」)。否則您的紀錄將無法正常運作。   
[![網域設定-GANDI04](https://www.cyberbiz.io/support/wp-content/uploads/網域設定-GANDI04.png)](https://www.cyberbiz.io/support/wp-content/uploads/網域設定-GANDI04.png)



5. 完成設定  
*若新增發生錯誤請看下方步驟 6  
[![網域設定-GANDI05](https://www.cyberbiz.io/support/wp-content/uploads/網域設定-GANDI05.png)](https://www.cyberbiz.io/support/wp-content/uploads/網域設定-GANDI05.png)



6. 若新增時發生錯誤訊息，請先將 Gandi 預設的 CNAME刪除後再進行設定。  
[![網域設定-GANDI11](https://www.cyberbiz.io/support/wp-content/uploads/網域設定-GANDI11.png)](https://www.cyberbiz.io/support/wp-content/uploads/網域設定-GANDI11.png)



* * *


📌 轉址設定  

1. 點選「域名」並選擇「網頁轉址」。  
[![網域設定-GANDI06](https://www.cyberbiz.io/support/wp-content/uploads/網域設定-GANDI06.png)](https://www.cyberbiz.io/support/wp-content/uploads/網域設定-GANDI06.png)



2. 點選「新增網頁轉址位址」。  
[![網域設定-GANDI07](https://www.cyberbiz.io/support/wp-content/uploads/網域設定-GANDI07.png)](https://www.cyberbiz.io/support/wp-content/uploads/網域設定-GANDI07.png)



3. 輸入內容  
【位置】: 選擇 http:// + https:// ，欄位 「空白」。(不要點擊框框)  
【轉址至】: http://，欄位「www.網域名稱.com」。(購買的網域)  
[![網域設定-GANDI08](https://www.cyberbiz.io/support/wp-content/uploads/網域設定-GANDI08.png)](https://www.cyberbiz.io/support/wp-content/uploads/網域設定-GANDI08.png)



4. 確認主網域轉址至子網域  
[![網域設定-GANDI09](https://www.cyberbiz.io/support/wp-content/uploads/網域設定-GANDI09.png)](https://www.cyberbiz.io/support/wp-content/uploads/網域設定-GANDI09.png)



* * *


📌 CYBERBIZ 轉址設定  
後台路徑 : 「管理中心」→「網域管理」  


1. 新增設定完的網域。(例 : www.網域名稱.com)
2. 勾起「總是將顧客重新導向到這裡」。
3. 確認綁定狀態「成功」。
[![網域設定-GANDI10](https://www.cyberbiz.io/support/wp-content/uploads/網域設定-GANDI10.png)](https://www.cyberbiz.io/support/wp-content/uploads/網域設定-GANDI10.png)

