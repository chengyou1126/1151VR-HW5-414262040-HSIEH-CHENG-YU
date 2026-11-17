# 1151VR-HW5 - 寶可夢精靈球收服小遊戲

## 1. 專案截圖
(你可以把截圖拖曳上傳到這裡，GitHub 會自動產生圖片語法)

## 2. GitHub 連結
https://github.com/chengyou1126/1151VR-HW5-414262040-HSIEH-CHENG-YU/new/main?filename=README.md

## 3. YouTube 影片連結
https://youtu.be/Bd1TW6dNFD4

## 4. 製作流程與相關操作說明

### 【製作流程】
1. **場景建置與角色導入**：於 Unity 6 中建置 3D 草原地形，佈置訓練家 Hilda 與 6 隻 Pikachu。
2. **物理引擎與碰撞判定**：撰寫 `BallWASD` 腳本控制精靈球移動；設定碰撞判定，當精靈球撞擊名字包含 "Pikachu" 的物件時，就觸發消除與爆炸特效。
3. **特效與音效整合**：為撞擊事件配置自製的原子彈等級核爆煙霧粒子特效 (`CaptureEffect`) 與震撼的爆炸音效。

### 【操作與注意事項】
- 使用鍵盤的 **WASD** 鍵遙控精靈球在地圖上滾動，依序撞擊 6 隻皮卡丘完成收服。
