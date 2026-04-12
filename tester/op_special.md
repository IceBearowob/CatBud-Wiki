# 在測試服內一些OP才能用的貓芽指令
## /provide [玩家ID] [份量參數]
給予[玩家ID][份量參數]的貓幣
### 份量參數
有四種，分別代表貓幣數量
- coin_3000
- coin_6000
- coin_20000
- coin_40000
## /code系列
### /code [禮品代碼] add [禮品金額] [有效天數]
新增禮品代碼
### /code [禮品代碼] remove
移除禮品代碼
### /code [禮品代碼] status
查詢禮品代碼狀態
## /erase [半徑範圍]
可以將[半徑範圍]內的實體給清除掉
### 半徑範圍
必須在0.0~99.9之間
## /hide
隱身，重複輸入可以切換
## /hosts
查詢玩家登入時使用的IP
## /room config [各種行為參數]
可以執行特定行為，像是強制進入副本之類的，下面開始介紹
## 魔幻之塔
### /room config layer [層數]
只能在魔幻之塔內使用，層數只能介於0~51層之間
### /room config enter
強制進入魔幻之塔
### /room config exit
強制離開魔幻之塔，只能在魔塔內使用
## 怪物浪潮
### /room config script
強制進入特定地圖，總共有三張地圖
- auditorium_0 (教堂)
- basement_0 (車站)
- dungeon_0 (地下城)
### /room config skip
跳過進度條，只能在浪潮內使用
### 天界聖戰
### /room config enter
強制進入天界
### /room config skip
跳過進度條，只能在天界內使用
## 空降戰域
### /room config terrain 
強制進入特定地圖，目前只有一張地圖
- countryside_0
## 緊急任務
### /room config script
強制進入地圖並指定boss，目前有兩種boss
- slime_0
- breeze_0
### /room config exit
強制結束緊急任務，只能在緊急任務內使用
### /room config execute
強制啟動緊急任務(可以讓所有列隊的玩家進入)
## 王者戰爭
### /room config execute
強制啟動王者戰爭(可以讓所有列隊的玩家進入)
### /room config exit
強制結束王者戰爭，只能在王者戰爭內使用
### /room config return
可以讓被淘汰的玩家原地返回繼續遊玩
### /room config terrain
強制進入特定地圖，目前只有一張地圖
- castle_0
## 爭奪貓盃
### /room config execute
強制啟動爭奪貓盃(可以讓所有列隊的玩家進入)
### /room config exit
強制結束爭奪貓盃，只能在爭奪貓盃內使用
### /room config return
可以讓被淘汰的玩家原地返回繼續遊玩
## 周年快樂
### /room config execute
強制啟動周年快樂(可以讓所有列隊的玩家進入)
### /room config exit
強制結束周年快樂，只能在周年快樂內使用
### /room config terrain
強制進入特定地圖，目前只有一張地圖
- castle_0