---
title: "LINE OA訊息提醒樣板設定"
last_modified: "2024-05-31"
categories: [第三方整合>LINE相關設定]
tags: []
permalink: "https://www.cyberbiz.io/support/?p=728"
---

![](https://www.cyberbiz.io/support/wp-content/uploads/適用站別.png)

[![](https://www.cyberbiz.io/support/wp-content/uploads/台灣站.png)](https://www.cyberbiz.io/support/?page_id=2490)

**功能說明：**  

* CYBERBIZ 設定 LINE推播，開啟「訂單」、「退貨」、「物流」、「顧客」、「定期訂單」樣板，在指定情境下自動回覆顧客相關的訊息。 

**操作目錄：**

* 訊息樣板設定
* 功能邏輯說明 

注意事項:  

* LINE OA 訊息會依LINE官方訊息方案費用計費 詳細收費請參考 [相關連結](https://tw.linebiz.com/column/budget-auto-count/)。
* 此功能需先串接好 Messaging API 功能，前往 [相關文件](https://www.cyberbiz.io/support/?p=706)。
* 使用此功能前需請商家開啟 LINE快速登入 或 [LINE OA 綁定官網會員](https://www.cyberbiz.io/support/?p=32679)，而會員登入或綁定後，得以收集 LINE UID 即可使用該功能。
* 會員需擁有 LINE OA好友(官方帳號)，才可以收到LINE OA訊息。



## 訊息樣板設定

1. 設定好 Messaging API功能，詳情請至 [LINE Messaging API](https://www.cyberbiz.io/support/?p=706) 文件設定。


2. 進入 CYBERBIZ 後台 ，可設定及開關相關功能。   
後台路徑 :「訊息推播」→「LINE OA 通知樣板」 [![訊息提醒樣版功能01](https://www.cyberbiz.io/support/wp-content/uploads/LINE-OA-訊息提醒樣板功能01.png)](https://www.cyberbiz.io/support/wp-content/uploads/LINE-OA-訊息提醒樣板功能01.png)



3. 點選欲啟用的提醒樣板。   
【Flex Message 樣板】  

* 設定是否啟用 : ON/OFF。
* 通知類型 : Flex Message 樣板/純文字。 
* 文字訊息 : 公版內容，可自行新增刪減內容。
*若需更改內文，請注意 {{ }} 中的內容，不要自行更動。(為自動抓取 CYBERBIZ 設定資料)  
*支援所有【訂單事件】&【物流事件】  
[![訊息提醒樣版功能02](https://www.cyberbiz.io/support/wp-content/uploads/LINE-OA-訊息提醒樣板功能02.png)](https://www.cyberbiz.io/support/wp-content/uploads/LINE-OA-訊息提醒樣板功能02.png)  


【純文字】 : 設定方法同上

[![訊息提醒樣版功能02](https://www.cyberbiz.io/support/wp-content/uploads/LINE-OA-訊息提醒樣板功能03.png)](https://www.cyberbiz.io/support/wp-content/uploads/LINE-OA-訊息提醒樣板功能03.png)





* * *

## 功能邏輯說明 (部分)

【貨物發送提醒】：出貨時發送。  
【貨物到店提醒】：一般物流到達「超商」時發送 (萊爾富、全家、7-11 ) 。  
【7-11 貨物到店提醒】：7-11 物流到達「超商」時發送。  
【貨物到門市提醒】：貨物到達「商家自己的門市」時發送。  
【定期訂單確認提醒】：會員成立第一筆訂單時發送訊息。(母訂單)  
【定期訂單出貨提醒】：每筆訂單成立時發送通知。(子訂單)  


