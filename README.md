# LineBot_with_Database
建立一個Line機器人並且搭配資料庫

先說明會用到以下幾個部分，需要安裝的東西會在每個部分逐步解釋
1. Line
2. SDK
2. Heroku平台
3. Database

## Line
請先到 <https://developers.line.biz/en/> 註冊自己的帳號吧。
完成之後我們來到Developer的首頁  
![developer_index](_v_images/_developer__1547797048_9334.png)  
有一個我已經本來就創建好的Provider了，剛申請好的帳號會是空的，這裡就按下"Create New Provider"，接下來會有一連串的確認名稱，公司等等之後按下結束。
![create_provider](_v_images/_create_pro_1547797612_14364.png)  

不過因為我已經有建立過了就不再建立了，完成之後回到上一張圖的介面我們把剛剛建立好的Provider選下去。
![channel_select](_v_images/_channel_se_1547797960_12153.png)  
  
![create_new_channel](_v_images/_create_new_1547798026_30629.png)  
  
我們選擇中間的"Messaging API"，進去後會進入一個輸入基本資料的介面依照所需的部分選取吧。  
這邊要注意帳號的名字"七天"才能修改一次，像我設定成"測試v0.1"就只能先這樣了。  
(那隻很可愛的貓是我的家貓歡迎追蹤 <https://www.facebook.com/catEchoLin/>)  
  
![channel_plan](_v_images/_channel_pl_1547798224_1229.png)  
再選擇方案的部分之後都可以再更動，所以先不需要太緊張，這邊就快速通過就好囉。  
在Confirm之前的記得把，下方的check box勾起來  
![channel_checkbox](_v_images/_channel_ch_1547799428_4948.png)  
申請完之後我們會來到BOT的設定之中同時你自己的帳號也會加入這個機器人成為好友。 
先階段可以嘗試一下左邊有一些基本的設定，不用寫程式也可以做一些文字或圖片等等的回覆，也能設定一些服務了。  
第一步份的建立就到這裡完成了。  

## SDK
接下來我們來安裝Line_BOT_SDK吧。




![message_setting](_v_images/_message_se_1547799334_6911.png)  

