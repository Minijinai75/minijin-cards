# minijin-cards — Minijin 的酒館角色卡發佈架

> **貼進酒館的網址請用 PNG 那欄**——酒館的網址直連匯入只吃 PNG（裸 JSON 會報 Unsupported file type）；raw.githubusercontent.com 在酒館預設白名單內，免設定直接通。JSON 欄留給「下載後用 Replace/Update 上傳」的手動路。
> 網址用英文檔名（中文檔名在 Discord 貼連結會被切斷）。中文檔名版本仍在倉內，內容相同。
> 這裡放的永遠是**最新版**的卡。網址固定不變——收藏一次，之後每次更新都從同一個網址拿。
> 卡片版本號寫在卡片裡（酒館的角色卡資訊面板可以看 `character_version`），檔名不帶版本號。

## 卡片清單

| 卡片 | 匯入網址（PNG） | 手動替換用 JSON | 說明 |
|---|---|---|---|
| 何思年（全時期 MVU 版） | [`hsn-full.png`](https://raw.githubusercontent.com/Minijinai75/minijin-cards/main/hsn-full.png) | [`hsn-full.json`](https://raw.githubusercontent.com/Minijinai75/minijin-cards/main/hsn-full.json) | 童年／學生／成年三線，變數卡。需要酒館助手＋ST-Prompt-Template |
| 何思年（一般版） | [`hsn-simple.png`](https://raw.githubusercontent.com/Minijinai75/minijin-cards/main/hsn-simple.png) | [`hsn-simple.json`](https://raw.githubusercontent.com/Minijinai75/minijin-cards/main/hsn-simple.json) | 免變數框架的輕量版。需要酒館助手 |
| 石睿（MVU 版） | [`shirui-mvu.png`](https://raw.githubusercontent.com/Minijinai75/minijin-cards/main/shirui-mvu.png) | [`shirui-mvu.json`](https://raw.githubusercontent.com/Minijinai75/minijin-cards/main/shirui-mvu.json) | 變數卡。需要酒館助手＋ST-Prompt-Template |
| 石睿（一般版） | [`shirui-simple.png`](https://raw.githubusercontent.com/Minijinai75/minijin-cards/main/shirui-simple.png) | [`shirui-simple.json`](https://raw.githubusercontent.com/Minijinai75/minijin-cards/main/shirui-simple.json) | 輕量版。需要酒館助手 |

> 角色原作：殭殭（授權 MINI 製作）／石睿為原創。

## 首次匯入

1. 複製上表檔案的**網址**（點進檔案 → Raw 的網址，或直接用發佈頁網址）
2. SillyTavern 角色卡面板 → 匯入 → **從外部網址匯入（External URL）** → 貼上網址
3. 或者：下載 JSON 檔，用一般的檔案匯入

## 更新已匯入的卡（重點功能）

卡片修了 bug、出了新版時，**不用刪卡重來**：

1. 打開該角色的卡片詳情 → 找「**Replace / Update（替換／更新）**」
2. 貼上**跟當初一樣的網址**（新版酒館支援直接貼網址；舊版就先下載檔案再上傳替換）
3. 完成——**聊天紀錄、好感度、變數全部保留**，只有卡片本體換新

> 酒館版本太舊看不到「貼網址」選項的話：從網址下載檔案 → Replace/Update 上傳，一樣保留聊天。

## 遇到問題

卡片玩起來怪怪的（狀態欄不動、數值凍結、格式跑掉），先確認你的卡是不是最新版（對一下 `character_version`），八成更新就好了。還是不行就到 Discord 告訴我：卡名＋版本號＋截圖。
