---
title: "美安shop.com串接"
last_modified: "2024-11-01"
categories: [第三方整合>美安串接,常見問題]
tags: []
permalink: "https://www.cyberbiz.io/support/?p=647"
---

![](https://www.cyberbiz.io/support/wp-content/uploads/適用站別.png)

[![](https://www.cyberbiz.io/support/wp-content/uploads/台灣站.png)](https://www.cyberbiz.io/support/?page_id=2490)

**功能說明：**  

* 增加新管道銷售您的商品。
* 經銷商會員人數活躍，有效增加品牌曝光。
* 串接美安SHOP.COM。

**操作目錄：**

* 美安串接
* 美安進行訂單測試
* 常見問題
* 美安聯絡資訊

注意事項:  

* 美安相關設定請洽美安客服詢問，此文件僅提供基礎教學。
* 商品 標籤欄位輸入「贈品」 
1. 該商品不會在美安顯示，在 CYBERBIZ 網站並不會受到影響。
2. 成立訂單時，帶有「贈品」標籤的商品金額，不會同步至美安。
3. 訂單取消/退貨時，「贈品」標籤商品的負項金額不會同步至美安。
* 美安商品xml，不包含有贈品標籤的商品及已下架的商品 。  
網址需要為英文跟數字，不能中文 。圖片必須使用 RGB 模式的 JPG 檔。

* 2022年前串接美安的顧客，串接前請先聯繫 CYBERBIZ 客服，開啟美安 API。
* 訂單一旦成立皆會抽成 (無論付款或出貨與否)，後續若商家在後台取消訂單或完成退貨處理，系統將再次回拋訂單已取消的資訊給美安，進一步扣除抽成金額。
* 美安訂單完成頁將呈現防詐騙通知，為美安訂單專屬功能。



## 美安串接

1. 店家須先向美安夥伴商店部門聯繫、完成簽約。
2. 收到美安發送的「美安台灣TW.SHOP.COM IT連接說明」的EMAIL再進行以下串接設定。  
[![美安shop.com串接01](https://www.cyberbiz.io/support/wp-content/uploads/美安shop.com串接01.png)](https://www.cyberbiz.io/support/wp-content/uploads/美安shop.com串接01.png)

3. 提供以下貴公司基本資料給美安。 
* 統編 
* 郵遞區號 
* 通訊地址 
* 收件人 
* 聯絡電話 
* Email 
* 佣金比例 
* 網站名稱 
* 網站網址(必須提供獨立的網址，您的網址不可附屬 CYBERBIZ 的子網域之下)   
舉例：  
請提供https://www.yourname.com.tw/，而非https://yourname.cyberbiz.co/



4. 美安會於收到完整資料的5個工作天內提供專屬的OFFER_ID與Advertiser_id


5. 將OFFER_ID與Advertiser_id填入後台  
後台路徑 :「第三方整合」→「美安 shop.com 設定」  
[![美安shop.com串接02](https://www.cyberbiz.io/support/wp-content/uploads/美安shop.com串接02.png)](https://www.cyberbiz.io/support/wp-content/uploads/美安shop.com串接02.png)

6. 檢查您的商品資訊是否符合美安規範  
串接美安您的商品需填入以下資訊，缺一不可，以避免後續設定有誤。  
設定方法可參考  
[商品管理-上架商品(單筆)](https://www.cyberbiz.io/support/?p=1958)  
[商品管理-上架商品 (EXCEL多筆)](https://www.cyberbiz.io/support/?p=1960)

* 商品名稱
* 商品網址(網址部分需要英文跟數字、不能中文) 商品簡述 圖片網址(圖片請務必使用 RGB 模式的 JPG 檔)
* 售價 
* 定價
* 產品編號 商品群組
[![美安shop.com串接03](https://www.cyberbiz.io/support/wp-content/uploads/美安shop.com串接03.png)](https://www.cyberbiz.io/support/wp-content/uploads/美安shop.com串接03.png)



7. 提供資訊給美安，提供完畢後請待美安後續相關測試。  

* 主機IP：請至 CYBERBIZ 後臺客服詢問 。
* 產品資料XML表
後台路徑 :「第三方整合」→「美安 shop.com設定」  
[![美安shop.com串接04](https://www.cyberbiz.io/support/wp-content/uploads/美安shop.com串接04.png)](https://www.cyberbiz.io/support/wp-content/uploads/美安shop.com串接04.png)




* * *

## 美安串接美安進行訂單測試

![](https://www.cyberbiz.io/support/wp-content/uploads/2021/12/fountain-pen.png)

* 若有相關疑問，請直接詢問美安窗口。
* 訂單為測試使用，不須實際出貨。
* 美安會以「美安測試」的名義下測試訂單，並以email通知您。
* 美安端會分別以不同操作方式下單三筆測試訂單，但最後只會有兩筆認列美安，另一筆則不是，此為正常狀況。




【回傳測試訂單報表】

後台路徑 :「第三方整合」→「美安 shop.com 設定」  
篩選出對應的時間並匯出訂單，將報表資料回傳給美安。  
*報表中應該包含RID、Click ID等資訊。  
[![美安shop.com串接05](https://www.cyberbiz.io/support/wp-content/uploads/美安shop.com串接05.png)](https://www.cyberbiz.io/support/wp-content/uploads/美安shop.com串接05.png)  


【取消測試訂單】

美安確認測試訂單成功後，會以e-mail通知您將測試訂單取消  
訂單取消後，請回覆email通知美安  
後台路徑 : 「訂單」→「美安訂單」  


1. 進入美安訂單並找到兩筆測試訂單 [![美安shop.com串接06](https://www.cyberbiz.io/support/wp-content/uploads/美安shop.com串接06.png)](https://www.cyberbiz.io/support/wp-content/uploads/美安shop.com串接06.png)
2. 點擊取消訂單  
[![美安shop.com串接07](https://www.cyberbiz.io/support/wp-content/uploads/美安shop.com串接07.png)](https://www.cyberbiz.io/support/wp-content/uploads/美安shop.com串接07.png)

3. 取消美安訂單  
維持系統自動帶入的訂單金額。不管是否完成付款，美安在訂單成立時即認單抽成，  
因此取消訂單時，還是要輸入訂單金額(不含運費) ，而不是輸入0
[![美安shop.com串接08](https://www.cyberbiz.io/support/wp-content/uploads/美安shop.com串接08.png)](https://www.cyberbiz.io/support/wp-content/uploads/美安shop.com串接08.png)

4. 回傳訂單取消紀錄給美安。  
[![美安shop.com串接05](https://www.cyberbiz.io/support/wp-content/uploads/美安shop.com串接05.png)](https://www.cyberbiz.io/support/wp-content/uploads/美安shop.com串接05.png)

5. 美安確認記錄正確後，表示串接完成。  
後續上線程序請洽美安。

* * *




## 常見問題



Q : 如何知道這筆訂單是不是從美安來的?

A : 「訂單」→「美安訂單」頁面內的訂單皆為美安訂單

* * *

Q : 什麼訂單狀態就會認列為美安訂單並被抽成呢?

A : 不論訂單付款狀態為何，訂單頁面下方操作記錄標示為「美安訂單已建立成功」，則美安即會抽成。  
若有訂單狀態為**付款失敗** 的美安訂單，還請留意需操作取消訂單來將此筆訂單從美安認列中扣除。  
*若有開啟「訂單自動取消」，因此被取消的美安訂單，抽成將會從美安認列中扣除。 

* * *

Q : 上傳產品資料xml檔出現失敗呢?

A : 請確認提供的商品資料xml中，必填欄位是否有缺漏，補填後再傳送一次即可。

* * *

Q : 如果我在官網上架新產品，我有需要再重新匯入一次產品資料xml檔嗎?

A : 產品資料xml檔只需要在串接時匯入一次即可，美安那邊會自動更新!  
商品在美安那邊的更新時間是以美安那邊來跟抓取資料為主，並非即時更新。

* * *

Q : 如果企業版操作部分退款，美安會退還退款部份抽成嗎?

A : 目前未支援部份退款機制，將計算整筆訂單抽成。

* * *

Q : 美安測試訂單相關問題?

A : CYBERBIZ 僅提供系統串接，不負責美安操作相關的服務。

* * *

Q : 定期定額與一頁式商店可以獲得美安回饋嗎?

A : 定期定額不行 一頁式可以

* * *

Q : 後臺傳給美安的訂單編號有任何限制嗎?

A : 目前傳給美安的訂單編號  
會判訂單編號若只有a~z、A~Z、# 等標示  
就會傳完成訂單名稱給美安  
如有不是上述字元存在，就只會傳送訂單編號的數字

* * *

美安聯絡資訊：  
客服專用電子信箱：twunfranchiseservices@markettaiwan.com.tw  
客服電話：02-87125598  
服務時間：週一至週五上午9:30–下午6:30  
週末及國定假日休息




