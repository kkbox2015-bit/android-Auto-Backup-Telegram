# android-Auto-Backup-Telegram
# 安卓免費備份到TG雲端無限空間
APP特點
手機拍完照可以立刻傳到TG備份（手機上就可以刪除不佔用空間）
目前手機空間不足趁睡覺背景運行批量上傳到TG 備份完馬上刪除手機上照片騰出空間
取代Line記事本功能 可放照片 影片 標題 要找檔案只要打開TG右上角按搜尋標題
可免費無限上傳到TG照片跟影片單檔案限制50MB以內 只要不超過畫質不壓縮不過期 超過程式也會幫你壓縮但畫質可能就下降（原本的line也是會壓縮畫質）
要傳送超過50MB影片建議自行打開TG上傳
檔案完全不經過開發者伺服器 都是直接手機對TG傳送 
適合族群：養貓狗大量紀錄照片和影片無限空間使用 不會像line會過期 也不佔用手機空間


需要先註冊安裝Telegram
1.創建官方機器人取得bot token（填入app用）
<img width="2102" height="3964" alt="1000092593" src="https://github.com/user-attachments/assets/9c4fc9f0-8ae8-4d8a-9784-01cedf731b25" />
打開Telegram最下方英文版選Chats 中文版選聊天室在到上方英文版是Search Chats 中文版搜尋聊天室 在此處輸入BotFather 一定要點頭像進入不能點右邊開啟
<img width="2944" height="1430" alt="1000092594" src="https://github.com/user-attachments/assets/ed96ec08-2e39-4939-8268-c4b82676f56b" />
<img width="1942" height="3946" alt="1000092595" src="https://github.com/user-attachments/assets/f144aef6-dd85-4811-8109-d1c5278d6197" />

在下方對話框輸入/newbot
會出現Alright a new ......一長串
再來輸入你的機器人名稱必須英文加底線_bot
上面已經有八百多萬個機器人非常容易重複名稱
出現Good. Now.....或Sorry,this代表已經重複
建議用一個英文單詞重複四次或五次比較少人用
例如youyouyouyou_bot直到他出現Done!開頭代表成功創立
請把下方的HTTP API:
8646280911:AAHtrkfjjdjdkdjcgfjjjjszbjtdn
這串代碼複製 
打開此次下載的app 
點設定自動備份（尚未設定）
<img width="2162" height="3986" alt="1000092596" src="https://github.com/user-attachments/assets/f65e2102-bd27-4d7e-9e87-030bfebfffd9" />

請貼上Bot Toekn這個格子就是貼上剛剛上面複製的再來按儲存
2.在打開TG創立要自動備份的群組名稱可以取寵物紀錄區 手機自動備份區 或記事本區
創立群組方法一樣打開Telegram最下方英文版選Chats 中文版選聊天室
右上角有垂直三個點的按鈕按下英文版選New group中文版選創立群組
在Whi would的輸入框裡面打@youyouyouyou_bot 就是你剛創立的機器人讓他加入在點右下方的箭頭
輸入中文聊天群組名稱在點右下角打勾
點你的群組名稱 點右上角有一隻編輯的筆 選Administrators 在點Add Admin 點你創立的機器人再點右上角打勾
再點add admin這次點右上角有一個放大鏡出現Search在裡面輸入@getidsbot
這邊要特別注意很多類似機器人名稱
<img width="3000" height="4000" alt="1000092600" src="https://github.com/user-attachments/assets/8c252fcb-44c1-4024-92ec-3c357a8a4301" />

請點那隻頭像有一個ID圖片 他的名稱有GetIDs Bot 跟getidsbot一樣點右上打勾
左上角點箭頭兩次返回到聊天室 就會看到聊天室id-1004458287請把他複製包含開頭的-
<img width="2184" height="4000" alt="1000092604" src="https://github.com/user-attachments/assets/0ffe22cb-e4b1-4549-9544-e29ca1edad6b" />

這時候就可以把getidsbot這隻機器人踢掉了 只留你的機器人
<img width="2852" height="3894" alt="1000092602" src="https://github.com/user-attachments/assets/509086a4-b018-4890-885a-a7efc1add2f6" />

在打開這次下載的APP點設定自動備份（尚未設定）
<img width="2162" height="3986" alt="1000092596" src="https://github.com/user-attachments/assets/12593ed9-d23e-4fd8-8045-a31c7d51d42a" />

把他貼在Chat ID 
選+新增 去找你手機儲存拍照的資料夾通常在DCIM再選Camera下方選使用這個資料夾 要備份其他資料也可自行更改再按驗證並儲存 就會看到已綁定你創立的群組
在把啟動資料夾自動備份上傳打開
開你的相機拍照 打開TG就會看到自動上傳了
app上的初始整批備份區一樣照上面的方法去創立機器人跟建立要備份的聊天室名稱及取得ID填入到app 綁定成功後
選要整批上傳的資料夾 按開始整批上傳 記得給背景運作權限才不會切其他APP被中斷
第三個就是取代line記事本的功能 一樣照上面創立 輸入此次紀錄標題 按開始上傳 
打開TG右上角就有放大鏡可以搜尋標題
這下安卓就擁有無限雲端空間了 不怕手機容量爆滿造成卡頓
