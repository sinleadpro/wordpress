---
title: "FACEBOOK 商業擴充套件－Step.2 網域驗證與事件設定"
last_modified: "2024-07-22"
categories: [第三方整合>Facebook相關設定,常見問題]
tags: []
permalink: "https://www.cyberbiz.io/support/?p=13973"
---

![](https://www.cyberbiz.io/support/wp-content/uploads/適用站別.png)
[![](https://www.cyberbiz.io/support/wp-content/uploads/台灣站.png)](https://www.cyberbiz.io/support/?page_id=2490)
[![](https://www.cyberbiz.io/support/wp-content/uploads/北美站.png)](https://www.cyberbiz.io/support/?page_id=32080)
[![](https://www.cyberbiz.io/support/wp-content/uploads/日本站.png)]() **功能說明：**  

* 使用者能夠在企業管理平台中認領網域的名稱擁有權，將您的網域綁至相對應的帳戶上，當驗證後就能控制鏈結和其他內容編輯權限，對於廣告投放也會有影響，除了可以擁有網站的使用權外，也可以避免被有心人士盜用。
**操作目錄：**

* 網域設定-DNS
* GANDI
* GODADDY
* 亞太
* HINET
* 網域設定-中繼標籤驗證
* QA常見問題
注意事項:  

* 注意各家網域驗證有不同的操作步驟，詳情請至相關公司網站內容做查詢，此網頁僅提供網域驗證操作步驟。
* **網域設定分別為 DNS 與中繼標籤驗證，建議您使用 DNS 系統，若仍然使用中繼標籤驗證來操作後台程式碼，若有操作失誤我司可不負後台程式修改責任。**


📌 網域設定-DNS(建議使用)  

請先進入[企業管理平台設定](https://business.facebook.com/settings/)。  

1. 點選「品牌安全」－「網域」，新增您的主網域名稱。  
[![fb網域驗證](https://www.cyberbiz.io/support/wp-content/uploads/2021/06/fb網域驗證2.png)](https://www.cyberbiz.io/support/wp-content/uploads/2021/06/fb網域驗證2.png)

2. 點選「DNS驗證」複製 TXT 紀錄，進入您**所屬網域廠商** 做設定  

* GANDI
* GODADDY
* 亞太
* HINET
[![fb網域驗證](https://www.cyberbiz.io/support/wp-content/uploads/2021/06/fb網域驗證3.png)](https://www.cyberbiz.io/support/wp-content/uploads/2021/06/fb網域驗證3.png)  

📍【GANDI】

1. 請先至 [網域設定-GANDI](https://www.cyberbiz.io/support/?p=13235) 將 **CNAME、轉址** 設定完成
2. 點選「域名」→「區域檔紀錄」→「新增」→「TXT」  
【單位】(預設)  
【名稱】輸入 @  
【文字參數】於 企業管理平台 複製的 TXT  

[![fb網域驗證](https://www.cyberbiz.io/support/wp-content/uploads/2021/06/fb網域驗證4.png)](https://www.cyberbiz.io/support/wp-content/uploads/2021/06/fb網域驗證4.png)  

📍【GODADDY】

1. 請先至 [網域設定-GODADDY](https://www.cyberbiz.io/support/?p=1) 將 **CNAME、轉址** 設定完成
2. 連接企業管理平台 
1. 進入 GoDaddy 後台－我的產品，點選右下角 DNS [![fb網域驗證](https://www.cyberbiz.io/support/wp-content/uploads/2021/06/fb網域驗證5.png)](https://www.cyberbiz.io/support/wp-content/uploads/2021/06/fb網域驗證5.png)
2. 進入 DNS 管理 ，新增一筆紀錄  
【類型】TXT  
【主機】輸入 @  
【TXT值】於 企業管理平台 複製的 TXT  
【TTL】1小時

[![fb網域驗證](https://www.cyberbiz.io/support/wp-content/uploads/2021/06/fb網域驗證6.png)](https://www.cyberbiz.io/support/wp-content/uploads/2021/06/fb網域驗證6.png)



📍【亞太】 進入亞太DNS後台，請依 **「CNAME」、「轉址」、「紀錄」、「TXT」** ，填寫完畢以下表格。  
[![fb網域驗證](https://www.cyberbiz.io/support/wp-content/uploads/2021/06/fb網域驗證7.png)](https://www.cyberbiz.io/support/wp-content/uploads/2021/06/fb網域驗證7.png)  

📍【HINET】

1. 請先至 [網域設定 – HINET](https://www.cyberbiz.io/support/?p=106) 將 CNAME、轉址設定完成。 


2. 設定完成後請至 [HiNet 網站](https://domain.hinet.net/#/)進行設定。   
後台路徑 :「我的網域」→「轉址服務 - 設定轉址」  

[![hinet01](https://www.cyberbiz.io/support/wp-content/uploads/fb網域驗證－HiNet01.png)](https://www.cyberbiz.io/support/wp-content/uploads/fb網域驗證－HiNet01.png)



3. 複製下方說明的 A記錄 IP位置。  
[![hinet02](https://www.cyberbiz.io/support/wp-content/uploads/fb網域驗證－HiNet02.png)](https://www.cyberbiz.io/support/wp-content/uploads/fb網域驗證－HiNet02.png)



4. 點選「我的網域」→「更新DNS記錄」。  
[![hinet03](https://www.cyberbiz.io/support/wp-content/uploads/fb網域驗證－HiNet03.png)](https://www.cyberbiz.io/support/wp-content/uploads/fb網域驗證－HiNet03.png)



5. 新增列表 
* A紀錄 :   
【主機名稱/別名】: 空白  
【紀錄類型】: A  
【IP/主機名稱】: IP位置

* TXT :  
【主機名稱/別名】: 空白  
【紀錄類型】: TXT  
【IP/主機名稱】: 貼上於 企業管理平台 複製的 TXT (前後請加上 ＂＂ 符號)＜－小寫

[![hinet04](https://www.cyberbiz.io/support/wp-content/uploads/fb網域驗證－HiNet04.png)](https://www.cyberbiz.io/support/wp-content/uploads/fb網域驗證－HiNet04.png)





6. 完成網域設定後，需等待2-3日，回到您企業管理平台，確認網域設定變成 「已驗證」 [![hinet](https://www.cyberbiz.io/support/wp-content/uploads/2021/06/fb網域驗證10.png)](https://www.cyberbiz.io/support/wp-content/uploads/2021/06/fb網域驗證10.png)


* * *


📌 網域設定-中繼標籤驗證  

請先進入[企業管理平台設定](https://business.facebook.com/settings/)  

1. 點選「品牌安全」－「網域」，新增您的主網域名稱。  
[![fb網域驗證](https://www.cyberbiz.io/support/wp-content/uploads/2021/06/fb網域驗證－中繼標籤驗證1.png)](https://www.cyberbiz.io/support/wp-content/uploads/2021/06/fb網域驗證－中繼標籤驗證1.png)

2. 點選「中繼標籤驗證」複製整段代碼   
**請注意！** FB只會驗證轉址過的網址  
如： yourname.com 轉址到 www.yourname.com  
若您的網域為子網域 如： shop.yourname.com 請確認已 CNAME 至 yourname.cyberbiz.co  
[![fb網域驗證](https://www.cyberbiz.io/support/wp-content/uploads/2021/08/fb網域驗證－中繼標籤驗證2.png)](https://www.cyberbiz.io/support/wp-content/uploads/2021/08/fb網域驗證－中繼標籤驗證2.png)

3. 進入 CYBERBIZ 後台  
**後台路徑 :** 「網站外觀」→「套版主題管理」→「程式碼編輯器」→「theme.liquid」  

[![fb網域驗證](https://www.cyberbiz.io/support/wp-content/uploads/fb網域驗證－中繼標籤驗證3.png)](https://www.cyberbiz.io/support/wp-content/uploads/fb網域驗證－中繼標籤驗證3.png)



4. 驗證成功 [![fb網域驗證](https://www.cyberbiz.io/support/wp-content/uploads/2021/06/fb網域驗證－中繼標籤驗證4.png)](https://www.cyberbiz.io/support/wp-content/uploads/2021/06/fb網域驗證－中繼標籤驗證4.png)


* * *


📌 QA常見問題  


Q1:我一定要**自己買網域嗎** ？  
A1:需要，才能完整設定**8個事件。**  

Q2:新增的事件**沒有影響** 刊登中的廣告，則內容的變更時間為何？  
A2:變更內容會**立即生效。**  

Q3:若刪除刊登中廣告的事件會怎樣?  
A3:受影響的廣告和廣告組合會**停止刊登** ，且**無法重新刊登。**  

Q4:若修改刊登中廣告的事件會怎樣?  
(例如重新排列事件的優先順序，或更改消費金額最佳化狀態)  
A4:受影響的廣告和廣告組合會自動**暫停刊登 3 天。**  

[詳盡內容以 Facebook
企業商家說明為主(連結至官網資訊)](https://www.facebook.com/business/help/422408905612648/)

