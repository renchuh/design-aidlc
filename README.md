design-aidlc 的中文指令速查表，給 TrendLife 設計師用。

設計師大多不用打指令，直接用中文跟 agent 說要做什麼就好。這份表是讓你知道「有哪些指令、什麼時候用」，並提供可以直接複製貼給 agent 的說法。

目前對應 design-aidlc **v0.4.0**。

## 怎麼用

用瀏覽器打開 `index.html` 即可。它是單一檔案，不需要安裝、不需要網路。

- 左側目錄跳到各章節，搜尋框可以找指令
- 有「複製」按鈕的區塊，按一下就能貼給 agent
- 灰色「範例」是對 agent 說的話，只供參考，用時換成你自己的專案和檔名
- 支援淺色與深色模式

## 內容

| 章節 | 說明 |
| --- | --- |
| 先看這裡 | 最常用的 4 個指令 |
| 日常流程 | 草稿 → 定稿協作 → 交付，每一步怎麼說 |
| 三種開始方式 | 依手上有什麼（Figma／圖片、需求、做好的 HTML）選路徑 A、B、C，另含補畫面、補需求的說法 |
| 在專案裡開始 | 在 omni-family、omni-SMB 使用 design-aidlc 的步驟 |
| Slash 指令 | `/design-aidlc` 系列 |
| 更新連動 | design-aidlc 有新版時，如何讓專案跟上 |
| 其他指令 | `new`、`draft`、`move`、`check` 等，附語法與範例 |
| Subagents | 各 subagent 的用途與說法 |
| doctor 對照 | `doctor` 與 `check` 出現的訊息怎麼處理 |

## 維護

內容來自 design-aidlc，這份表不是來源。design-aidlc 發新版時：

1. 對照新版的變更（`bin/design-aidlc.ts`、各 `cli.ts`、`skills/design-aidlc/`、`docs/prompts.zh-TW.md`）
2. 修改 `index.html`
   - 其他指令：`CLI` 陣列（指令名稱、語法、說明）和 `EXAMPLES`（範例）
   - Subagents：`AGENTS` 陣列
   - 其他章節：直接改 HTML
3. 更新側欄的版本號和日期（`.ver`）與本檔的「目前對應」版本

指令的語法、旗標、行為以 design-aidlc 的程式碼為準。兩邊不一致時，以 design-aidlc 為準。
