# 提醒每天喝水的Telegram_bot

## 動機發想
因為現代人太常喝飲料，以至於時常忘了喝水，然而喝水又很重要，因此我們決定做一個telegram bot 來提醒大家喝水

## 所需設備
- Raspberry pi 3 
- USB 轉 TTL 傳輸線 
- 電腦

## 接線方式
![image](https://github.com/lulala88/WaterLuLaLa_bot/blob/master/圖片1.png)
## 建立Telegram_bot
![image](https://github.com/lulala88/WaterLuLaLa_bot/blob/master/49407159_402289950513843_7869862137751928832_n.png)
![image](https://github.com/lulala88/WaterLuLaLa_bot/blob/master/49378818_1126747494162752_8568655971100917760_n.png)
   
## 安裝套件
- python-telegram-bot
- telegram.ext                                                              
- telepot
- con
- beautifulsoup4
- requests
- json
- Emoji   
- schedule    
- time                                                                             
- logging                                                                             

## 指令介紹
### start - to begin with a cool picture
### help - get some help 
### daily_demand - know how much water you need 
### weather - Puli's weather
## 參考資料
1. 將Telegram_bot設置在
https://www.instructables.com/id/Set-up-Telegram-Bot-on-Raspberry-Pi/

2. Telegram_bot 
https://github.com/python-telegram-bot/python-telegram-bot/wiki/Extensions-–-Your-first-Bot

3. 計算一天喝水量
https://www.morewater.com.tw/QA.aspx

4. python 參考  
https://github.com/dbader/schedule#h3

5. python crontab
https://github.com/dbader/schedule

6. 天氣資訊 
https://works.ioa.tw/weather/api/doc/index.html
https://github.com/comdan66/weather/blob/master/README.md

7. 表情 
https://github.com/python-telegram-bot/python-telegram-bot/wiki/Emoji
https://www.webfx.com/tools/emoji-cheat-sheet/

8. requests
https://blog.gtwang.org/programming/python-requests-module-tutorial/

## 工作分配
106213014 資管二  歐芷欣 /daily_demand & 定時提醒  
106213019 資管二  蘇美婷 /weather
