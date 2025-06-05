---
title: "CKEDITOR-文章編輯器教學"
last_modified: "2025-02-24"
categories: [網站設定>前台介面]
tags: []
permalink: "https://www.cyberbiz.io/support/?p=21070"
---

![](https://www.cyberbiz.io/support/wp-content/uploads/2021/09/wp-主視覺bar-1024x321.png) ![](https://www.cyberbiz.io/support/wp-content/uploads/2021/08/全版本.png) **功能說明：**  

41. 如何使用CKEditor(文章編輯器)設計銷售頁、著陸頁。 
42. 文字、圖片及影片上傳教學，含建議規格。 
43. 應用範圍：商品頁、商品群組、活動頁（一頁商店）、定期定額、部落格、其他頁面等。 
**操作目錄：** CKEditor 介紹  
文字  
圖片上傳  
- 尺寸規格   
- 個別/批次上傳   
- 常見問題-移除圖片之間空白格   
影片上傳  
常見問題  
狀況一 :  
youtube嵌入的影片，後面的圖片及內文不見了？  
狀況二 :  
youtube嵌入的影片無法隨螢幕縮放，手機版會爆出去，或是顯示太小了？  
狀況三 :  
商品頁面跑版或是編輯器內容預覽看不到(前台顯示正常)？  
注意事項:  

* 請勿直接複製其他網頁或是檔案內容貼上編輯器，請使用純文字貼上按鈕來貼入內容後再上圖，以免帶到其他語法造成跑版或是顯示異常。 


CKEditor 介紹  

後台路徑 :「商品」→「所有商品」→「商品管理」→「商品描述」  

以商品介紹為例，【規格說明】、【運送方式】設定方式皆相同。  

[![CKEITOR-文字編輯器01](https://www.cyberbiz.io/support/wp-content/uploads/2022/01/CKEITOR-文字編輯器01-1.png)](https://www.cyberbiz.io/support/wp-content/uploads/2022/01/CKEITOR-文字編輯器01-1.png)  

**【文字】**  

在CKEditor 中編輯的文字，可直接視為前台頁面顯示的預覽圖。  
此為功能簡單範例  
*若使用其他文字軟體匯入 CKEditor (如: Office)，格式須符合CKEditor 制定格式。  

[![CKEITOR-文字編輯器02](https://www.cyberbiz.io/support/wp-content/uploads/2021/09/CKEITOR-文字編輯器02.png)](https://www.cyberbiz.io/support/wp-content/uploads/2021/09/CKEITOR-文字編輯器02.png)  
進階設定教學。  

[![CKEITOR-文字編輯器03](https://www.cyberbiz.io/support/wp-content/uploads/2021/09/CKEITOR-文字編輯器03.png)](https://www.cyberbiz.io/support/wp-content/uploads/2021/09/CKEITOR-文字編輯器03.png)
[錨點教學影片](https://www.cyberbiz.io/support/wp-content/uploads/2021/09/錨點設定.mp4)  


**【圖片上傳】**  

·尺寸規格  
圖片上傳限制:2mb/每次上傳量  
圖片 SEO 請至 SEO 優化教學 做設定。  
*圖片寬度超過 1110 px 會自動壓縮至 1110 px  
*圖片寬度不得大於 5000 px、長度不得大於7000 px   

·製作長幅產品圖建議  

1. 一張圖完成。(不會有空格問題，但要注意圖片上傳大小)  
寬度 1000 px / 長度不限  

2. 多張圖拼湊。(圖片檔案小，但要注意圖片尺寸是否可達成無縫長條圖)  
寬度 1000 px / 長度1000 px

[![CKEITOR-文字編輯器04](https://www.cyberbiz.io/support/wp-content/uploads/2021/09/CKEITOR-文字編輯器04.png)](https://www.cyberbiz.io/support/wp-content/uploads/2021/09/CKEITOR-文字編輯器04.png)  
·個別/批次上傳  


1. 上傳照片可選擇透過 CKEditor 圖片按鈕逐一上傳，也可透過資料夾一次上傳圖片。
個別上傳 批次上傳

44. 前台畫面顯示  

[![CKEITOR-文字編輯器07](https://www.cyberbiz.io/support/wp-content/uploads/2021/09/CKEITOR-文字編輯器07.png)](https://www.cyberbiz.io/support/wp-content/uploads/2021/09/CKEITOR-文字編輯器07.png)



45. 常見問題- 圖片之間有空白格  
原因 : 若逐一上傳並在照片之間按下 ENTER鍵，則網頁顯示會多一行空白格。  

[![CKEITOR-文字編輯器09](https://www.cyberbiz.io/support/wp-content/uploads/2021/09/CKEITOR-文字編輯器09.png)](https://www.cyberbiz.io/support/wp-content/uploads/2021/09/CKEITOR-文字編輯器09.png)

**解決方案**  
方法一、  
進入後台點選「原始碼」  
取代所有的 < p > < /p > 調整為 < div > < /div > ，就不會再出現空白格。  
*此解法僅能解決圖片可自動換行的情況。  
範例 :  
A : 兩張圖片寬度皆為 300 px ，則無法透過程式碼將空白格刪除，圖片之間必有空白。  
B : 兩張圖片寬度皆為 1000 px ，若圖片之間按下 ENTER 後，可利用程式碼來將空白格刪除。  

[![CKEITOR-文字編輯器10](https://www.cyberbiz.io/support/wp-content/uploads/2022/01/CKEITOR-文字編輯器10.png)](https://www.cyberbiz.io/support/wp-content/uploads/2022/01/CKEITOR-文字編輯器10.png)  

方法二、  
點選圖片「影像屬性」將寬度設為 100% ，高度維持原狀  

設定完成  

[![CKEITOR-文字編輯器08](https://www.cyberbiz.io/support/wp-content/uploads/2021/09/CKEITOR-文字編輯器08.png)](https://www.cyberbiz.io/support/wp-content/uploads/2021/09/CKEITOR-文字編輯器08.png)  

**【影片上傳】**  


1. 影片相關設定 請至 [影片自動播放+特定播放時間](https://www.cyberbiz.io/support/?p=19650)設定教學   

[![CKEITOR-文字編輯器11](https://www.cyberbiz.io/support/wp-content/uploads/2022/01/CKEITOR-文字編輯器11.png)](https://www.cyberbiz.io/support/wp-content/uploads/2022/01/CKEITOR-文字編輯器11.png)



2. 前台畫面顯示  

[![CKEITOR-文字編輯器12](https://www.cyberbiz.io/support/wp-content/uploads/2021/09/CKEITOR-文字編輯器12.png)](https://www.cyberbiz.io/support/wp-content/uploads/2021/09/CKEITOR-文字編輯器12.png)

* * *

常見問題  

**【狀況1】 : youtube嵌入的影片，後面的圖片及內文不見了？**  
原因 : 因為圖片及內文被影片語法包住，導致下方內容無法顯示。  

![CKEditor](https://www.cyberbiz.co/support/wp-content/uploads/2020/04/CKEditor13.png)
![CKEditor](https://www.cyberbiz.co/support/wp-content/uploads/2020/04/CKEditor14.png) 解決方法 :  
點擊原始碼，將除了影片以外的<div>語法刪除  
※紅色框框刪除  
※藍色框框改成<p> 及 </p>  
只要是文字或是圖片，前面都使用p語法 注意:影片前面( < iframe >前面) 的< div > 語法不可以拿掉喔！
![CKEditor](https://www.cyberbiz.co/support/wp-content/uploads/2020/04/CKEditor15.png)  

**【狀況2】 : youtube嵌入的影片無法隨螢幕縮放，手機版會爆出去，或是顯示太小了？**  
原因 : 因為youtube嵌入的影片被圖片或是文字的語法 <p>包住了。  

![CKEditor](https://www.cyberbiz.co/support/wp-content/uploads/2020/04/CKEditor16.png) 解決方法 :  
1. 請點擊原始碼  
2. 將紅匡的 <p> 改成 <div class="embed-responsive embed-responsive-16by9">  
3. 藍匡的 </p> 改成 </div>  
![CKEditor](https://www.cyberbiz.co/support/wp-content/uploads/2020/04/CKEditor17.png)
![CKEditor](https://www.cyberbiz.co/support/wp-content/uploads/2020/04/CKEditor18.png)  

**【狀況3】 : 商品頁面跑版或是編輯器內容預覽看不到(前台顯示正常)？**  
原因 : 因為商品頁編輯器中的 <style type="text/css">p, li { white-space: pre-wrap; } <
/style> 語法導致跑版。  
● 通常比較常發生在，從其他網站複製內容貼到編輯器時發生，因為會帶到其他網站的語法。  
![CKEditor](https://www.cyberbiz.co/support/wp-content/uploads/2020/04/CKEditor19.png)  
![CKEditor](https://www.cyberbiz.co/support/wp-content/uploads/2020/04/CKEditor22.png)  
解決方法 :  
1. 請點擊原始碼  
2. 找到 <style type="text/css">p, li { white-space: pre-wrap; } < /style > 的語法，刪掉這段即可  
![CKEditor](https://www.cyberbiz.co/support/wp-content/uploads/2020/04/CKEditor20.png)
![CKEditor](https://www.cyberbiz.co/support/wp-content/uploads/2020/04/CKEditor21.png)

