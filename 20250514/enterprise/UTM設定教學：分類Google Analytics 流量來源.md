---
title: "UTM設定教學：分類Google Analytics 流量來源"
last_modified: "2022-09-14"
categories: [第三方整合>Google相關設定,TW台灣站]
tags: []
permalink: "https://www.cyberbiz.io/support/?p=6434"
---

![](https://www.cyberbiz.io/support/wp-content/uploads/適用站別.png)
[![](https://www.cyberbiz.io/support/wp-content/uploads/台灣站.png)](https://www.cyberbiz.io/support/?page_id=2490)
[![](https://www.cyberbiz.io/support/wp-content/uploads/北美站.png)](https://www.cyberbiz.io/support/?page_id=9206)
**功能說明：**  

* 設定 UTM 紀錄用戶們來自於 Facebook、Line、Blog…等管道。
* 三大好處 : 目標顧客的來源、制定行銷方案、發掘潛在客戶。
* 應用情境 :
1. 同時使用社群媒體推廣網站或是商品連結，分析各管道的點擊情況。(可區分 EDM、Email、LINE OA) 
2. 與知名KOL、網紅及明星線上合作，透過 UTM 標記，商家可了解每位合作人各自的成效。 
3. 利用 QRCode可張貼廣告至公車看板、捷運看板及各類文宣宣傳，可分析不同類型的使用者成效。 
**操作目錄：**

* 什麼是 UTM
* 為什麼要用 UTM
* UTM 要如何看
* UTM 使用技巧
* UTM 設定
注意事項:  

* 教學文件僅提供基礎 UTM 概念教學，詳細概念操作、障礙排除 CYBERBIZ皆不提供協助，請至外部資源查詢。
* 參數大小寫要一致：Facebook/cpc ≠ Facebook/CPC。
* 參數內請勿放重要的資訊：由於參數是放在連結，而連結任何人點入後皆能看到，所以重要的資訊包含個資等都不建議加進 UTM 中。 
* 埋設UTM碼並不影響網站SEO，搜尋引擎會自動忽略UTM參數，因此無須擔心 UTM 會影響網站 SEO。

📌 什麼是 UTM 是 Google Analytics 提供給數據分析員能夠自行填入的連結標記， 在原本的網址中加入適當的參數，方便在Google
Analytics 後台查詢數據的內容， 例如流量的點擊次數，整體活動成效、跳出率及瀏覽間…等。  

* * *

📌 為什麼要用 UTM 清楚的知道  
客戶從哪裡來 UTM 可以協助商家紀錄流量來源以及媒介，包含社群、網站、EDM、LINE推播…等，同時也可以知道哪一個網紅、KOL帶來的流量最好。 A/B
Test  
測試行銷風格 透過不同的行銷素材、文案以及代言人，埋設不同的參數即可進行交叉檢測，直接從 GA 後台就可掌握數據。 行銷管道  
分配運用 透過 UTM 商家可以更清楚的鎖定會員以及消費者，有效的節省傳統廣告的成本，測試過後即可提供資源至最有價值的行銷管道。  

* * *

📌 UTM 要如何看 廣告活動來源 廣告活動來源Campaign Source（必填）
網站的流量來源、導流量的網站。例如：Google搜尋引擎、Facebook、部落格等。 **範例** : utm_source=blog 廣告活動媒介
廣告活動媒介Campaign Medium（必填）
使用的網站流量媒介，讓你分辨識哪個裝置點擊。例如：Email、關鍵字廣告、Banner、Email、CPC、廣告..等。 **範例** :
utm_medium=email 廣告活動名稱 廣告活動名稱Campaign Name（建議填寫） 這次活動廣告的名稱，讓你能在後台數據中較好分辨活動。
例如 : 雙11、周年慶…等。(建議可填入日期，才可知道活動起始點) **範例** : utm_campaign=1111 付費關鍵字廣告字詞
付費關鍵字廣告字詞Campaign Term（開放式填寫） 通常是為了這組廣告下的關鍵字廣告字詞、連結名稱或是替案圖片文字。 **範例** :
utm_term=flower ，flower 是這次廣告下的關鍵字。 廣告活動內容 廣告活動內容Campaign Content（開放式填寫）
用來識別一個廣告裡面會有兩種內容（A/B Test時）連結網站，方便辨別二者。 **範例** :  
utm_content=Alink  
utm_content=Blink  

* * *

📌 UTM 使用技巧 [![utm使用技巧](https://www.cyberbiz.io/support/wp-content/uploads/UTM設定教學01.png)](https://www.cyberbiz.io/support/wp-content/uploads/UTM設定教學01.png) 1.UTM中的參數英文大小寫一致
UTM參數的大小寫會影響它在GA後台中的數據成效顯現，像是臉書的參數應用：FB、Facebook、facebook建議統一使用一種模式比較好，這樣數據的呈現才會統一。
2.UTM中不應該有空格或特殊符號 UTM參數中如果含有空格與特殊符號很容易造成判斷失效，像是空格會讓網址產生亂碼，而某些特殊符號在 UTM
格式中含有自己的意思，例如：「?」、「&」、「#」就有本身的含義，不建議使用。如果想要使用特殊符號，Google 官方是建議使用「+」、「_」類型比較適合。
3.盡量使用英文字母 中文字在網址連結上通常會呈現一段很長的亂碼，如果參數都呈現如此，則會導致分析 UTM的人出錯率也提高。  4.建立一個UTM總表
你不會記得每個做好的UTM總長名稱，就算你記得，你的共同使用者也不一定會記，最好致做一個UTM的綜合大表，將以往至今的UTM都放在上面，追蹤成效時才能更加方便又快速！  

* * *

📌 UTM 設定

1. 進入 [Campaign URL Builder](https://ga-dev-tools.web.app/campaign-url-builder/) 設定相關內容，如何填寫請看上方 UTM 要如何看。  
[![設定utm](https://www.cyberbiz.io/support/wp-content/uploads/UTM設定教學02.png)](https://www.cyberbiz.io/support/wp-content/uploads/UTM設定教學02.png)



2. 下方會自動生成連結，如果認為連結太長可以設定短網址。  
[![utm連結、短網址](https://www.cyberbiz.io/support/wp-content/uploads/UTM設定教學03.png)](https://www.cyberbiz.io/support/wp-content/uploads/UTM設定教學03.png)



3. 進入 GA3 查看數據。  
[![ga畫面](https://www.cyberbiz.io/support/wp-content/uploads/UTM設定教學04.png)](https://www.cyberbiz.io/support/wp-content/uploads/UTM設定教學04.png)




