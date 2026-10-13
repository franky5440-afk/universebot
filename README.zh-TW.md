# Universe Bot

**一個總管，一整隊 AI，全在你的電腦上。**

[English](README.md) · [網站](https://universebot.si/zh-tw/) · [下載](https://universebot.si/zh-tw/download/) · [安裝說明](https://universebot.si/zh-tw/docs/install/) · [常見問題](https://universebot.si/zh-tw/docs/faq/)

Universe Bot 是 Mac 和 Linux 的桌面 app，把 AI agent 做成通訊軟體裡的聯絡人。你跟總管講需求，總管分派給隊員，彼此傳訊息、回報結果，整個過程你都看得到，隨時可以插話。

用的是你自己登入的 Claude、ChatGPT、Gemini，或你自己申請的 API key。全部在你的電腦上執行。

> **公開測試期間免費，正在找測試者。** 模型費用依你使用的服務計算（你的訂閱額度或 API 帳單）。回報問題的方式見[意見回饋](#意見回饋)。

![委派工作：總管傳訊息給隊員，隊員做完回報](https://universebot.si/screenshots/zh-tw/delegation.webp)

## 能做什麼

- **每個 agent 都是獨立的人**：名字、頭像、人格、規則、記憶各自設定。
- **每個 agent 自己選模型**：雜事交給便宜的模型，難的交給強的。Claude、ChatGPT（Codex）、Gemini 的訂閱，以及相容 OpenAI 格式的 API key（例如 OpenRouter）都能混用。
- **委派像傳訊息**：總管把工作傳訊息給隊員，不用乾等，好幾個隊員可以同時做。
- **看得到用量、可以清 session**：每個 agent 有自己的用量面板；對話太長太貴就按「清除 session」，記憶、人格、規則都還在。
- **例行任務**：每天、每週、每月自動派工；電腦關機錯過的那一次，開機後會補跑。
- **會自己開瀏覽器，卡住就交給你**：遇到登入或驗證需要真人，會請你接手，你弄完它再繼續。
- **用手機跟總管對話**：透過 Telegram 或 iMessage，跟桌面上是同一段對話。
- **iPhone／iPad 手機 app**（TestFlight 公開測試中，[加入測試](https://testflight.apple.com/join/5J2N7Mdg)）：在外面也能看所有 agent、跟總管對話，訊息全程加密。
- **權限由你決定**：每個 agent 四種權限等級，從只能對話到能讀寫工作資料夾；上網搜尋只有你在畫面上能打開。

| | |
|---|---|
| ![每個 agent 選自己的模型](https://universebot.si/screenshots/zh-tw/models.webp) | ![每個 agent 的用量面板](https://universebot.si/screenshots/zh-tw/usage.webp) |
| ![權限等級](https://universebot.si/screenshots/zh-tw/permissions.webp) | ![Telegram 與 iMessage 設定](https://universebot.si/screenshots/zh-tw/messaging.webp) |

## 下載

目前版本 **0.3.0**。

| 平台 | 檔案 |
|---|---|
| Mac，Apple 晶片（已經 Apple 公證） | [UniverseBot-arm64.dmg](https://download.universebot.si/latest/UniverseBot-arm64.dmg) |
| Mac，Intel（已經 Apple 公證） | [UniverseBot-x64.dmg](https://download.universebot.si/latest/UniverseBot-x64.dmg) |
| Linux x64（AppImage） | [UniverseBot-x86_64.AppImage](https://download.universebot.si/latest/UniverseBot-x86_64.AppImage) |

需求：macOS 13 以上，或有桌面環境的 Linux x64。另外至少要有一樣：用你自己帳號登入的 Claude Code、Codex CLI 或 Gemini CLI，或你自己申請的 API key。第一次開 app 時，開始畫面會檢查缺什麼、給你可以複製的安裝指令。完整步驟見[安裝說明](https://universebot.si/zh-tw/docs/install/)。

## 意見回饋

現在是公開測試版，你的回饋最重要。挑你方便的方式：

- 在這個 repo **[開 issue](../../issues/new/choose)**（回報問題或建議）。
- 想私下講，**寄信**到 support@universebot.si。

請**不要**把 API key、密碼、配對碼或私人對話貼進 issue，這裡的 issue 是公開的。

## 關於這個 repo

這個 repo 放 Universe Bot 的公開說明、版本紀錄和問題回報。app 的原始碼不在這裡公開。

Universe Bot 是 Frank Lin 的個人專案，跟 Anthropic、OpenAI、Google 沒有關係，也不是 Discord 上那個同名的 bot。

© Frank Lin. All rights reserved.　[隱私權說明](https://universebot.si/zh-tw/privacy/)
