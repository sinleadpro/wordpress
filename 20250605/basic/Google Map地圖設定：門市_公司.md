---
title: "Google Map地圖設定：門市/公司"
last_modified: ""
categories: [網站設定>前台介面]
tags: []
permalink: "https://www.cyberbiz.io/helpcenter/?p=420"
---

在前台顯示門市/公司地圖，正常顯示如下：  
![Google Map地圖|464x194](https://www.cyberbiz.co/helpcenter/wp-content/uploads/2019/09/MAP1.png)

_Step 1  _先至Google Map上，打上想顯示的地址→點選【分享】→點選【嵌入地圖】→點選【複製HTML】

![Google Map地圖|464x229](https://www.cyberbiz.co/helpcenter/wp-content/uploads/2019/09/MAP2.png)

> **功能列表**
>
> 後台路徑 :「網站外觀」→「套版主題管理」→「網站設定」→「客服」  
>

_Step 2
_到後台【網站外觀】→【套版主題管理】→【網站設定】→【客服中心】→【地圖連結】，將剛剛所複製的【HTML碼】貼上，並儲存設定，即可在前台顯示地圖。

![Google Map地圖](https://www.cyberbiz.co/helpcenter/wp-content/uploads/2019/09/MAP3.png)

\---狀況題1：前台預設文字為【公司地址】，若想改成【門市位置】或其他文字，要怎麼改？---

到後台【外觀設置】→【樣板編輯器】→選擇【contact.liquid】→找到紅線顯示的此行，將紅框內的文字改為想顯示的文字，儲存設定後即可變更。  
![Google Map地圖](https://www.cyberbiz.co/helpcenter/wp-content/uploads/2019/09/MAP4.png)

狀況題2：除了預設資訊外，想要顯示其他資訊要怎麼做？  
例如：今天想加上傳真電話

![Google Map地圖](https://www.cyberbiz.co/helpcenter/wp-content/uploads/2019/09/MAP5.png)

到後台「網站外觀」→「套版主題管理」→「選擇操作」→「CSS/HTML編輯器」→選擇【 contact.liquid 】→將其中一段< li >至< /li
>複製起來（反白部分）  
![Google Map地圖](https://www.cyberbiz.co/helpcenter/wp-content/uploads/2019/09/MAP6.png)

將剛剛複製的段落，貼在< /ul >上方，並且將複製後的紅底線刪除（不要刪到原本紅底線的部分），直接填寫想要的資訊（如下方紅框處），儲存設定後即可變更。  
![Google Map地圖](https://www.cyberbiz.co/helpcenter/wp-content/uploads/2019/09/MAP7.png)

