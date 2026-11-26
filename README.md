# LazyOS

**Think More. Do Less. Human Intent. AI Execution.**

一份 AGENTS.md，任何 AI 都能用。支援 Claude Code、OpenAI Codex、Google Antigravity。

## 使用

1. 下載 [AGENTS.md](AGENTS.md)，放進你的工作目錄。
2. 在該目錄啟動 AI，直接交代任務。
3. 專案專屬的指引寫在 `<!-- LAZYOS:END -->` 這一行下面。

同一目錄如果有 CLAUDE.md 或 GEMINI.md，部分平台會優先讀它們而略過 AGENTS.md。這時在它們裡面寫一句「請先讀 AGENTS.md」。

## 專案已經有 AGENTS.md

不要直接複製覆蓋。macOS 檔名預設不分大小寫，小寫的 agents.md 也會被蓋掉。

把 LazyOS 的內容貼到原檔最上面，包含開頭與結束標記。原本的專案指引留在結束標記下面。

團隊共用的儲存庫要先想清楚。提交之後，同事使用的 AI 也會讀到 LazyOS。

## 更新

對 AI 說「更新 LazyOS」。AI 會從檔案開頭標記裡的來源取得新版，只替換開頭標記到結束標記之間的內容，專案指引保持不動。

目前版本寫在 AGENTS.md 第一行的標記裡。
