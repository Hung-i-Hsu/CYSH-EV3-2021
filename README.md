# CYSH-EV3
國立嘉義高級中學 110學年度第一學期 LEGO EV3 機器人專題

### 一 、 說明

此為嘉義高中110學年度第一學期 高三多元選修 LEGO EV3 機器人專題 第一小組之 GitHub 倉庫

我們將每一次上課實際撰寫之程式碼上傳 GitHub ，記錄每一次課程進度 。

維護者 ： Hung-i, Hsu

### 二 、 運行環境

 * Windows 10
 > Windows 10 Home 21H1
 >
 > Windows 10 Pro 1809

 * LEGO EV3 主機韌體
 > EV3_Firmware_V1.09H

 * LEGO EV3 程式編譯器
 > LEGO® MINDSTORMS® Education EV3 ( EV3 Lab Software Education V 1.4.5_English )
 >
 >*下載網址 : https://education.lego.com/en-us/downloads/retiredproducts/mindstorms-ev3-lab/software

### 三 、 檔案詳細資訊及介紹

* 20210908_EV3_Alpha_1.ev3
> 以EV3螢幕播放笑臉圖示，間隔一秒鐘後以黃、紅、綠燈光各播放1秒鐘。
> 
> 播放完螢幕及燈光後，以音量 100 說出 EV3 內建 「 Hello 」 語音一次，接著，以自訂義方式，播放一次《卡農》部分樂曲。
>
> 以下為程式碼之圖片
> 
> ![20210908_EV3_Alpha_1_P1](https://user-images.githubusercontent.com/62639434/146936137-ffe631fa-332f-49b4-ab2c-feb5712b9c1d.png)
> ![20210908_EV3_Alpha_1_P2](https://user-images.githubusercontent.com/62639434/146936401-6005f578-2037-4d45-9e60-a8755d7357a3.png)
> ![20210908_EV3_Alpha_1_P3](https://user-images.githubusercontent.com/62639434/146936779-cea75af9-7782-4026-b06a-0ccffbc553a5.png)
> ![20210908_EV3_Alpha_1_P4](https://user-images.githubusercontent.com/62639434/146936830-2a5c0983-da99-4a19-accc-0cdffd47383e.png)
> ![20210908_EV3_Alpha_1_P5](https://user-images.githubusercontent.com/62639434/146936864-81101505-a789-4d30-be33-a41ef700f4f0.png)
> ![20210908_EV3_Alpha_1_P6](https://user-images.githubusercontent.com/62639434/146936884-a1f1ef64-79a7-4a13-88cd-e41cefac1ef7.png)

* 20210908_EV3_Alpha_2.ev3
> 為20210908_EV3_Alpha_1.ev3修正音樂及加長之版本。

* 20210908_EV3_Alpha_3.ev3
> 為20210908_EV3_Alpha_2.ev3修正音樂及加長之版本。

* 20210908_EV3_Alpha_4.ev3
> 為20210908_EV3_Alpha_3.ev3修正音樂及加長之版本。

* 20210915_EV3_Project_01_1.ev3
> 以20210908_EV3_Alpha_4.ev3為基礎，加長音樂，增加 EV3 馬達作動，以及增加程式碼可讀性。
>
> 第一、二行意義：執行程式碼按鈕及 EV3 本體顏色顯示及 Smile 圖示展示，加入馬達作動，以當時地板環境進行 90 度繞圈，速度 50 。
> 
> 第三行至十一行意義：以指定C、D、E、F、G、A、B方式拼接為播放《卡農》，並加入等待時間作為休止符。以適當斷行及連結增強可讀性。
>
> 以下為程式碼之圖片
> 
> ![20210915_EV3_Project_01_1_P1](https://user-images.githubusercontent.com/62639434/146938682-fde6589a-d19d-4064-a68c-4b187be53c95.png)
> ![20210915_EV3_Project_01_1_P2](https://user-images.githubusercontent.com/62639434/146963547-ceec4691-9356-4120-a989-4b11213113f1.png)
> ![20210915_EV3_Project_01_1_P3](https://user-images.githubusercontent.com/62639434/146963586-e2def23d-8c46-4274-827f-f50bd565bdd1.png)

* 20210915_EV3_Project_01_2.ev3
> 以20210915_EV3_Project_01_1.ev3為基礎，修正音樂休止符作用，修正 EV3 馬達作動參數。

* 20210915_EV3_Project_01_3.ev3
> 以20210915_EV3_Project_01_2.ev3為基礎，修正音樂、音樂休止符作用，移除 EV3 馬達作動。

* 20210915_EV3_Project_02_1.ev3
> 以Project_01進行創意發想之創意版本。
>
> 以下為程式碼之圖片
> 
> ![20210915_EV3_Project_02_1_P1](https://user-images.githubusercontent.com/62639434/146940141-391da370-e1d3-4587-9bff-10d175ed2443.png)
> ![20210915_EV3_Project_02_1_P2](https://user-images.githubusercontent.com/62639434/146940195-f7f1740a-a606-4be4-9131-34c157fdd17e.png)

* 20210929_EV3_Project_03_1.ev3
> 加入以距離感測器判斷距離之功能，用 EV3 主機螢幕顯示表情 ( 喜愛與生氣 ) 。
> 
> 並使用20210915_EV3_Project_01_2.ev3之音樂。
>
> 以下為程式碼之圖片
> 
> ![20210929_EV3_Project_03_1_P1](https://user-images.githubusercontent.com/62639434/146941460-e8d51524-9b9e-4738-9d23-060864960f62.png)

* 20210929_EV3_Project_03_2.ev3
> 以20210929_EV3_Project_03_1.ev3為基礎，修正螢幕顯示表情但燈光顏色錯誤之程式碼。
>
> 以下為程式碼之圖片
> 
> ![20210929_EV3_Project_03_2_P1](https://user-images.githubusercontent.com/62639434/146941877-a4b7fb89-a210-423a-a964-79a4c64c16ba.png)

* 20211006_EV3_Project_04_1.ev3
> 全新專案，嘗試以Touch Sensor撰寫自走車程式碼。
> 
> 當Touch Sensor無碰觸到東西回傳數值時， EV3 自走車以馬達速度50且燈光為綠色之方式行走。
> 
> 當Touch Sensor碰觸到東西回傳數值時， EV3 自走車提示音播出，左右馬達以速度 -50 ， 1.5 圈直行，再以左右馬達速度 -28 ， 1 圈 51 度右旋，並且燈光為紅色。
> 
> 整組程式碼為循環不斷，達成自走車效果。
>
> 以下為程式碼之圖片
> 
> ![20211006_EV3_Project_04_1_P1](https://user-images.githubusercontent.com/62639434/146943319-038e5c4b-67b2-43a8-b55f-7d4ed13fbe5f.png) 

* 20211006_EV3_Project_05_1.ev3
> 以20211006_EV3_Project_04_1.ev3為基礎，但完全改變程式碼內容。
> 
> 加入二次判斷機制，流程如下圖
> ![20211006_EV3_Project_05_1_流程圖](https://user-images.githubusercontent.com/62639434/146946047-48c1ed2b-2281-442a-9357-303fd01f425e.png)
>
> 而A、B、C、D指令分別為 ： 
>
> A. 馬達停止運動，並以音量 100 播放 「 Airbrake 」音檔。
>
> B. 左右馬達以 -50 速度倒退 0.5 秒，再以左右馬達 50 速度前進 0.5 秒。
>
> C. 左右馬達以 -50 速度倒退 0.5 秒，再以左右馬達 50 速度右轉 0.5 秒。
>
> D. 左右馬達以 50 速度前進 0.4 秒，並點亮黃燈。
>
> 整組程式碼為循環不斷，達成自動判斷效果。
> 
> 以下為程式碼之圖片
> 
>![20211006_EV3_Project_05_1_P1](https://user-images.githubusercontent.com/62639434/146957893-67f8c8ff-cf8e-4cef-8a67-8e527b1406ea.png)

* 20211020_EV3_Project_06_1.ev3
> 此專案為全新單元，用於以Color Sensor進行環境判斷。
>
> 在此程式碼內，Color Sensor分別會判斷下列顏色，並做出相對應的提示音、表情以及燈號。
>
> 1. 偵測到黑色 > 播放 「 Black 」 音檔，並在 EV3 主機螢幕呈現 「 Angry 」，以及綠色燈號。
>
> 2. 偵測到藍色 > 播放 「 Blue 」 音檔，並在 EV3 主機螢幕呈現 「 Dizzy 」，以及黃色燈號。
>
> 3. 偵測到白色 > 播放 「 White 」 音檔，並在 EV3 主機螢幕呈現 「 Love 」，以及紅色燈號。
>
> 4. 偵測到紅色 > 播放 「 Red 」 音檔，並在 EV3 主機螢幕呈現 「 Tear 」，以及綠色燈號。
>
> 5. 偵測到綠色 > 播放 「 Green 」 音檔，並在 EV3 主機螢幕呈現 「 Tear 」，以及黃色燈號。
>
> 6. 偵測到黃色 > 播放 「 Yellow 」 音檔，並在 EV3 主機螢幕呈現 「 Tear 」，以及紅色燈號。
>
> 整組程式碼為循環不斷，達成自動判斷效果。
> 
> 以下為程式碼之圖片
> 
> ![20211020_EV3_Project_06_1_P1](https://user-images.githubusercontent.com/62639434/146960857-ea2ca708-5df5-4d09-8e84-776bb7715268.png)
> ![20211020_EV3_Project_06_1_P2](https://user-images.githubusercontent.com/62639434/146960894-d024d761-1e61-423b-963e-02b921126233.png)

* 20211020_EV3_Project_07_1.ev3
> 當Color Sensor切換為環境光檢測時，如果光亮度大於 25 單位，音量 100 播放 「 OH-oh 」 音檔，並亮起紅色燈號。
>
> 否則亮綠燈。
>
> 整組程式碼為循環不斷，達成自動判斷效果。
>
> 以下為程式碼之圖片
> 
> ![20211020_EV3_Project_07_1_P1](https://user-images.githubusercontent.com/62639434/146961657-95c071eb-85a4-408a-b623-d5de8dea9782.png)

* 20211027_EV3_Project_08_1.ev3
> 當Color Sensor切換為環境光檢測時，如果光亮度小於 6 單位，則速度 50 左轉 20 度。
>
> 否則判斷是否大於 17 單位，是則速度 50 右轉 30 度；否則速度 50 直行。
>
> 整組程式碼為循環不斷，達成自動判斷效果。
>
> 以下為程式碼之圖片
> 
> ![20211027_EV3_Project_08_1](https://user-images.githubusercontent.com/62639434/146962958-278d5d24-bc78-44fe-a28c-1d5c58784817.png)

* 20211027_EV3_Project_09_1.ev3
> 此版本程式碼包含多項功能：
>
> 1. Color Sensor判斷綠色、紅色，如果為綠色、紅色，則馬達速度 30 直行，並且亮起黃色燈號。否則停止運動。
>
> 2. Color Sensor判斷黑色、紅色，如果為綠色、紅色，則停止運動。否則馬達速度 30 直行並且亮起黃色燈號。
>
> 兩組程式碼皆為循環不斷，達成自動判斷效果。同時，兩者為相反邏輯，一為偵測顏色運動，另一者為偵測顏色而不動。
> 
> 以下為程式碼之圖片
> 
> ![20211027_EV3_Project_09_1_P1](https://user-images.githubusercontent.com/62639434/146964632-ee868b00-ba6e-4887-afef-c3b257952416.png)
> ![20211027_EV3_Project_09_1_P2](https://user-images.githubusercontent.com/62639434/146964652-7649b074-7beb-4bad-8b62-f2926e33af5d.png)

* 20211027_EV3_Project_10_1.ev3
> 此程式碼為20211020_EV3_Project_07_1.ev3為基礎，進行改良及加強功能。
>
> 當Color Sensor為環境光檢測時，如果光亮度大於 10 單位，則馬達速度 30 直行，且音量 100 播放 「 OH-oh 」 音檔，間隔 1 秒鐘，並亮起紅色燈號。
>
> 否則馬達停止運動。
>
> 整組程式碼為循環不斷，達成自動判斷效果。
>
> 以下為程式碼之圖片
> 
> ![20211027_EV3_Project_10_1_P1](https://user-images.githubusercontent.com/62639434/146965442-3957d240-717d-465d-91ea-09608e0fb3d5.png)

* 20211103_EV3_Project_11_1.ev3
> 此程式碼為全新專案，用於超音波感測器偵測。
>
> 當超音波感測器感測距離小於 5 公分，則馬達速度 50 ， 50 度右轉 1.2 圈。
>
> 否則馬達速度 50 直行 0.1 圈。
>
> 整組程式碼為循環不斷，達成自動判斷並自走效果。
>
> 以下為程式碼之圖片
> 
> ![20211103_EV3_Project_11_1_P1](https://user-images.githubusercontent.com/62639434/146966256-fa6846f5-5cd2-4d15-8110-19241ff7fe1a.png)

* 20211103_EV3_Project_12_1.ev3
> 當超音波感測器感測距離大於 75 公分，則馬達停止作動。
>
> 否則超音波感測器感測距離繼續判斷是否小於 50 公分，成立則馬達停止作動；否則馬達速度 50 直行。
>
> 整組程式碼為循環不斷，達成自動判斷效果。
>
> 以下為程式碼之圖片
> 
> ![20211103_EV3_Project_12_1_P1](https://user-images.githubusercontent.com/62639434/146967259-0c0be3d5-23a2-4982-9bb6-4b65df579f4a.png)

* 20211124_Color Sensor_Test.ev3
> 此程式碼為Color Sensor接線測試專用，成功連結則播放 「 Hello 」音檔。
>
> 以下為程式碼之圖片
> 
> ![20211124_Color Sensor_Test_P1](https://user-images.githubusercontent.com/62639434/147026025-afc1dd48-c4f3-4f10-b161-fca9c83b0311.png)


* 20211124_LR Motor_Rest.ev3
> 此程式碼為左右馬達校正專用，成功校正則復歸 ( 0 , 0 ) 位置。
>
> 以下為程式碼之圖片
> 
> ![20211124_LR Motor_Rest_P1](https://user-images.githubusercontent.com/62639434/146968220-27fbe446-5ed5-4ce0-a13b-3fc8ead60e03.png)

*  20211124_Middle Motor_Test.ev3
> 此程式碼為雙頭馬達測試專用，成功測試則持續以馬達速度 -100 作動。
>
> 以下為程式碼之圖片
> 
> ![20211124_Middle Motor_Test_P1](https://user-images.githubusercontent.com/62639434/146968571-56f89ff5-d0cd-4cb5-9c82-dde39954eb46.png)

* 20211124_Touch Sensor_Test.ev3
> 此程式碼為Touch Sensor接線測試並成功觸碰測試專用，成功觸碰則播放 「 Hello 」音檔。
>
> 以下為程式碼之圖片
> 
> ![20211124_Touch Sensor_Test_P1](https://user-images.githubusercontent.com/62639434/147026037-135024c4-8890-40b6-b447-ad361b6e35e6.png)

### 四 、 硬體除錯紀錄

在學習的過程之中，我們曾經更新韌體，但不明原因導致 EV3 軟體出錯，韌體無法更新且無法開機。

參考官方說明手冊，我們成功修復 EV3 ，步驟為下：

1.以 USB 纜線連接 EV3 及電腦並打開 EV3 程式編譯器。

2.同時按下 EV3 主機之取消鍵、確認鍵、向右鍵。

3.接著 EV3 主機會強制重新啟動，此時放開取消鍵。

4.當 EV3 螢幕顯示「Updating」時，請放開其餘兩個按鍵。

5.EV3 程式編譯器此時即可更新 EV3 韌體。
