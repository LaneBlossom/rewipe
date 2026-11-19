# Rewipe → FF14 擴充

FF14 高難副本的**錄影與復盤**。作者：LaneBlossom

**Rewipe 現在分成兩個部分**：通用的錄影、播放、拍照程式 **[ReFlo](https://github.com/LaneBlossom/reflo)**，和裝在它裡面的 **FF14 擴充**（就是這裡）。功能跟 Rewipe 一樣，之後的更新也都在這兩個地方。

> **Rewipe** = **Rewind**（倒帶）＋ **wipe**（滅團）——滅團了，就倒帶回去看看哪裡出錯。

## FF14 擴充有什麼

- **ACT 連線**：開打自動錄影、滅團或通關自動停，每場一個檔或串成一個長檔
- **復盤**：載入 ACT log 或 FFLogs 網址，時間軸和影片自動對齊，點事件就跳到那一刻
- **死因與 debuff**：每次死亡顯示死於哪一招、死前受到的傷害；誰在哪個機制吃了什麼 debuff
- **Overlay**：即時 DPS / rDPS / aDPS、團減、死因和死亡紀錄、副本與戰鬥狀態
- **Rewink**：插入角色名、副本名，通關後提示拍紀念照
- 招式與副本名稱使用遊戲內官方繁中

錄影、播放與擷取片段、壓縮、Overlay 主題、Rewink 拍照框這些通用功能在 ReFlo 本體（[ReFlo 操作手冊](https://github.com/LaneBlossom/reflo/blob/main/MANUAL.md)）。FF14 功能的詳細用法（ACT 設定、FFLogs 金鑰、自動錄影、Overlay 的 DPS／團減／死因）目前在 [Rewipe 操作手冊](MANUAL.md)，裝了擴充的 ReFlo 畫面跟它一樣。

## 已經在用 Rewipe？

打開 Rewipe，上方會出現「Rewipe 之後改成『ReFlo ＋ FF14 擴充』」，按 **一鍵搬家**：

1. 自動下載 FF14 擴充和 ReFlo 安裝程式（都會先驗證）。
2. 按「關掉 Rewipe 並安裝 ReFlo」，照安裝程式的步驟裝好。
3. ReFlo 第一次開啟時會問「要匯入 Rewipe 的設定嗎？」，按 **匯入**。

設定、FFLogs 金鑰、ACT 資料夾、Overlay 主題、Rewink 的貼紙和版型都會帶過去；錄影照樣存到原本的資料夾。Rewipe 的檔案不會被改動，確認沒問題後可以自己解除安裝 Rewipe（不一定要）。

沒看到提示（例如關掉了「自動檢查更新」）也可以手動搬：照下面「新安裝」裝好 ReFlo，第一次開啟時一樣會問要不要匯入 Rewipe 的設定。

## 新安裝

1. 到 [ReFlo 的下載頁](https://github.com/LaneBlossom/reflo/releases/latest) 安裝 ReFlo。
2. 到 👉 **[這裡的 Releases](../../releases)** 下載最新的 `ffxiv-x.x.x.reflo-ext`（標籤是 `ext-ffxiv-v…`）。
3. 打開 ReFlo，右上角 ☰ →「擴充功能」→「從檔案安裝」，或直接把 `.reflo-ext` 檔拖進 ReFlo 的視窗。
4. 按「立即重新開啟」，錄影頁就會出現「FF14 附加功能」。

之後 ReFlo 會自動檢查擴充的新版，有新版時 ☰ 上會有小圓點，到「擴充功能」按一下就能更新。

ReFlo 只會安裝作者簽章過的擴充檔，檔案被改過就不會安裝或載入。

## 需求

- ReFlo（Windows 10 / 11，64 位元）
- 使用 ACT 功能需要 ACT（FFXIV_ACT_Plugin，建議加裝 OverlayPlugin 才看得到倒數和戰鬥狀態）；使用 FFLogs 需要自己的免費 API 金鑰（軟體內有教學）

## 舊版 Rewipe

Rewipe 1.x 的安裝檔還留在 [Releases](../../releases)，但之後不再更新。

## 授權與著作權

© 2026 [LaneBlossom](https://github.com/LaneBlossom)，保留所有權利。

FF14 擴充和 Rewipe 可以免費下載、個人使用，也歡迎分享下載頁面的連結。但**未經作者同意，請勿反編譯或解開程式、交給 AI 或其他工具分析改寫、修改、重新散布或以它為基礎製作類似的軟體**。完整條款見 [LICENSE](LICENSE)。

## 非官方工具聲明

FF14 擴充和 Rewipe 是玩家自製的**非官方工具**，與 SQUARE ENIX CO., LTD. 及 FINAL FANTASY XIV 各地區的營運商無關，未獲其授權、贊助或認可。FINAL FANTASY、FINAL FANTASY XIV、FFXIV 是 Square Enix 集團的商標或註冊商標。

- 不包含、也不散布遊戲的資料檔；招式與副本名稱是在你自己的電腦上，從你安裝的遊戲、你自己的戰鬥紀錄或 FFLogs 讀取。
- 不修改遊戲程式或檔案，不讀寫遊戲的記憶體，也不攔截遊戲的網路封包。
- ACT、FFXIV_ACT_Plugin、OverlayPlugin、RTSS、FFLogs 是各自作者的軟體與服務，沒有內附在這裡，也與這裡無關。
- 使用第三方工具可能違反遊戲的使用條款，風險由使用者自行承擔。完整條款見 [LICENSE](LICENSE)。
