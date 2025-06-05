---
title: "新版 VIP 群組標籤"
last_modified: "2024-04-16"
categories: [PLUS版適用,會員>VIP設定]
tags: []
permalink: "https://www.cyberbiz.io/helpcenter/?p=8621"
---

![](https://www.cyberbiz.io/helpcenter/wp-content/uploads/一般版3.png)
![](https://www.cyberbiz.io/helpcenter/wp-content/uploads/PLUS版3.png)
**功能說明：**  

分群經營，可針對不同客層設定不同VIP規則。

1. **全館VIP：** 全館會員適用。
2. **VIP群組：** 可設定綁定會員標籤的 VIP群組，讓特定會員套用不同於 全館VIP 的規則。 
* 若同一位會員身上有兩種標籤，則視標籤群組的排序來決定該會員適用的 VIP群組。
* 若顧客有設定 「VIP群組標籤」，但未在此 VIP 中，可以查看是否為「未達 VIP群組 最低層級門檻」導致，只要顧客有達門檻就會立即升級。

**操作目錄：**

優化前

* 觸發計算時機
* 加減標籤的回推計算
* 加減標籤後的新效期
* 舊邏輯範例情境

優化後

* 觸發計算時機
* 加減 VIP 群組標籤的回推計算
* 加減標籤後的新效期
* 新邏輯範例情境 (加標籤)
* 新邏輯範例情境 (加標籤)
* 優化說明

注意事項:  

* VIP 群組標籤優化 於 2022/08/31 上線，詳細說明請查看此篇教學文件。
* VIP群組排序，會從最下面開始篩選，建議將條件最嚴苛的排在最下面！  
情境: VIP已發佈，若標籤群組內原本有顧客，商家把該標籤群組的標籤從顧客身上移除，則該標籤群組則會失去標籤，店家需要另外複製版本重新幫群組設定標籤。



## **優化前**

## 📌 優化前 : 觸發計算時機

只要幫會員加上或移除任何顧客標籤，都會觸發 新版VIP 的計算。  

* * *

## 📌 優化前 : 加減標籤的回推計算

【規則】

* 加標籤：視為無效訂單成立，以最近一筆有效訂單去往前推效期計算 VIP門檻。
* 減標籤：視為無效訂單成立，以最近一筆有效訂單去往前推效期計算 VIP門檻。


* * *

## 📌 優化前 : 加減標籤後的新效期

【系統計算後若等級產生更新】

* 產生升等：以「加減標籤當天」做為新效期起始日，以最近一筆有效訂單加上效期期間作為截止日。
* 產生降等：以「加減標籤當天」做為新效期起始日，以最近一筆有效訂單加上效期期間作為截止日。 


* * *

## 📌 優化前 : 舊邏輯範例情境

【優化前 : 條件設定】  
設定全館VIP及VIP群組，

* 全館VIP : 「一般會員、銀卡、金卡」三個等級。
* VIP群組 : 綁定「VIP」顧客標籤，群組包含一個會員層級。
[![vip標籤01](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤01old.png)](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤01old.png)  

【優化前 : 案例說明 】  
某會員在 2022/1/1 生效新版VIP版本成為一般會員，此會員過去有兩筆有效訂單。  
(分別為 2020/12/5、2021/12/1)  
[![vip標籤03](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤03.png)](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤03.png)  

【優化前 : 訂單累積金額計算方式】  
商家加了顧客標籤，無論是否與 VIP群組 有關，皆會觸發 新版 VIP 計算。  
(系統查看前一筆有效訂單發生於 2021/12/1 09:00:40，並從 2020/12/1 09:00:40 起算至 2021/12/1
09:00:40。)  
[![vip標籤04](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤04.png)](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤04.png)  

【優化前 : 加減標籤後的新效期】  
以加標籤當天 2022/4/1 09:00:53 作為起始日，用前一筆有效訂單 2021/12/1 09:00:40 往後加 365天，  
等於 2022/12/01 23:59:59 為新效期截止日，對消費者實際會員效期不變，僅有前台顯示效期看起來會不滿365天。  
(等級 : 一般會員 → 銀卡會員)  
[![vip標籤05](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤05.png)](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤05.png)  



* * *

## **優化** 後

## 📌 優化後 : 觸發計算時機

幫會員加上或移除跟 「VIP群組」綁定的標籤才會觸發 新版VIP優化 的計算。  

* * *

## 📌 優化後 : 加減 VIP 群組標籤的回推計算

【規則】

* 加標籤：視為有效訂單成立，由加標籤當下回推效期計算 VIP門檻。
* 減標籤：視為無效訂單成立，以最近一筆「有效訂單成立」 或 「加標籤」的事件回推效期計算 VIP門檻。


* * *

## 📌 優化後 : 加減標籤後的新效期

【系統計算後若等級產生更新】

* 產生升等：以「加減標籤當天」做為新效期起始日，再加上效期期間作為截止日。
* 產生降等：以離當下最近的「加標籤」或「有效訂單成立」事件日期作為新效期起始日，再加上效期期間作為截止日。 


* * *

## 📌 優化後 : 新邏輯範例情境 (加標籤)

【優化後 : 條件設定】  
設定全館VIP及VIP群組，

* 全館VIP : 僅有「一般會員」一個等級。
* VIP群組 : 綁定「VIP」顧客標籤，群組包含兩個會員層級。

[![vip標籤01](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤01.png)](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤01.png) [![vip標籤02](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤02.png)](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤02.png)


【優化後 : 案例說明 】  
某會員在 2022/1/1 生效 新版VIP版本成為一般會員，過去有一筆有效訂單。  
[![vip標籤06](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤06.png)](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤06.png)  

【優化後 : 訂單累積金額計算方式】  
商家加了 VIP 群組綁定的 VIP 顧客標籤，觸發新版 VIP 計算。  
因綁定VIP群組標籤視為有效訂單。  
(系統以當下時間看過去 365天，從2021/4/1 09:00:53 起算至 2022/4/1 09:00:53 。)  
[![vip標籤07](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤07.png)](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤07.png)  

【優化後 : 加減標籤後的新效期起始日】  
以加標籤當天2022/4/1 09:00:53作為起始日，往後加365天，等於2023/4/1
23:59:59為效期截止日，對消費者來說是完整的365天效期。  
[![vip標籤08](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤08.png)](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤08.png)  



* * *

## 📌 優化後 : 新邏輯範例情境 (減標籤)

【優化後 : 條件設定】  
設定全館VIP及VIP群組，

* 全館VIP : 僅有「一般會員」一個等級。
* VIP群組 : 綁定「VIP」顧客標籤，群組包含兩個會員層級。

[![vip標籤01](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤01.png)](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤01.png) [![vip標籤02](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤02.png)](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤02.png)


【優化後 : 案例說明 】  
某會員原本是一般會員，在2022/4/1商家加了「VIP」顧客標籤，升等銀卡會員。  
[![vip標籤09](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤09.png)](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤09.png)  

【優化後 : 訂單累積金額計算方式】  
商家於 2022/4/10 09:00:53 減「VIP」顧客標籤，因此系統會回推前一筆「有效訂單」計算 VIP 門檻。  
(故從2022/4/5 09:00:40回推至2021/4/5 09:00:40。)  
[![vip標籤10](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤10.png)](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤10.png)  

【優化後 : 加減標籤後的新效期起始日】  
系統會回推前一筆「有效訂單」或「加標籤」事件計算 VIP 門檻，2022/4/5 09:00:40 作為新效期起始日，往後加365天，等於2023/4/5
23:59:59為效期截止日。  
[![vip標籤11](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤11.png)](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤11.png)  



* * *

## 📌 優化說明

1. 新舊邏輯並存 : 
* 若商家在優化上線後，幫顧客增加VIP綁定標籤 或 顧客產生有效訂單，將使用新邏輯。
* 若商家在優化上線後，未幫顧客增加VIP綁定標籤 或 顧客未產生有效訂單，將使用舊邏輯。 
* 若商家在優化上線前，幫顧客增加 任何標籤，上線後產生無效訂單或減標籤，皆使用舊邏輯。 


![](https://www.cyberbiz.io/support/wp-content/uploads/fountain-pen.png)

* 建議商家在正常操作下使消費者切換到新邏輯，因不會對消費者權益造成影響，故商家不需額外於前台通知消費者。
* 不建議商家為了換成新邏輯而統一幫會員減標籤再加標籤，因為可能發生會員被降等的狀況，請見下方範例。

💡請見下方範例 :  

【條件設定】  
假設會員效期 30 天，有設定全館VIP及VIP群組，群組內僅有一個VIP等級，門檻為累積消費滿 100 元。  
[![vip標籤12](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤12.png)](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤12.png)  

【流程時間序】  


* 2022/04/01 幫會員加VIP標籤並下一筆$50元有效訂單，未達VIP等級門檻故等級不變。
* 2022/04/30 再下一筆$50元有效訂單，因消費累積達$100故升等為VIP，效期到2022/5/30。 
[![vip標籤13](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤13.png)](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤13.png)

* 2022/5/1 優化功能上線。
* 2022/5/20 減掉VIP標籤，便不屬於VIP群組會員，成為全館VIP會員，新效期為2022/4/30-2022/5/30。 
[![vip標籤14](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤14.png)](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤14.png)  


* 2022/5/20 再接著加上VIP標籤，以新邏輯計算，往前回推30天效期，從2022/4/20起算至2022/5/20僅累積消費$50元，依然是全館VIP會員。  
[![vip標籤15](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤15.png)](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤15.png)

* 因等級不變，全館VIP會員效期維持 2022/4/30-2022/5/30。  

[![vip標籤16](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤16.png)](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤16.png)




2. 截止日優化項目全面更新:   
關於效期的截止日優化將會在上線後一併更新到所有會員，使消費者前台顯示效期與商家設定會員效期相符。  

💡 請見以下範例 :  

【優化上線前】  
假設會員效期 30 天，2022/4/1 有一筆有效訂單，等級不變。  
2022/4/15 加標籤後，系統查看前一筆有效訂單發生於2022/4/1，往前回推30天效期假設有符合升等，便以加標籤當天2022/4/15
為升等後新效期起始日，以一筆有效訂單加30天效期2022/5/1為截止日，但消費者在前台看起來效期不滿完整30天。  
[![vip標籤17](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤17.png)](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤17.png)  

【優化上線後】  
前台更改顯示，升等後新效期起始日改為2022/4/1，截止日照樣是2022/5/1，使消費者在前台看起來效期有滿完整30天，不影響到總效期天數。  
[![vip標籤18](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤18.png)](https://www.cyberbiz.io/support/wp-content/uploads/新版-VIP-群組標籤18.png)



* * *

