# AGENTS.md：食品科學概論 學生網頁（公開 repo / GitHub Pages）

給在這個 repo 工作的 AI agent（Codex、Claude Code）。這個 repo **公開**，只放學生看的網頁，任何人都看得到。

## 開工與收工

1. 開工：`git pull`。這台筆電上有**兩份**本 repo 的 clone（Codex 一份、Claude Code 一份），不 pull 就會推出衝突。
2. 交接簿 `進度.md` 和詳細規則在**私人** repo `Tai-ShengYeh/intro-food-science-a2-src`（筆電路徑 `D:\course\Intro_Food_Science\Intro_Food_Science\A2_投影片工程\`）。開工先讀它的 `AGENTS.md` 與 `進度.md`，收工在 `進度.md` 加一筆。
3. 收工：commit、push。commit 訊息寫清楚改了哪幾週、哪一種頁面。

## 一定要遵守

- **`.gitignore` 是白名單**：只公開 `index.html`、`intl.html`、`general.html` 和三種週次頁（`*_投影片.html`、`*_互動教學.html`、`*_A2互動練習.html`）。前後測、題庫、教案、原始碼、成績解碼器**絕對不可加進來**，前後測公開會污染後測。
- **不要從產生器重 build 第 2–18 週的頁面**。線上頁面除了產生器的內容，還有 Codex 事後直接改 HTML 加上的課堂活動、雙語案例、出處與中文主講動畫頁。重 build 會把這些洗掉。要改已發布頁面就直接改 HTML，並在 `進度.md` 記一筆。
- 頁面裡的 YouTube 影片：
  - 投影片封面後「先看動畫」：A2 教學動畫。
  - 「看影片」：《超級後廚》片段。
  - 「再看短片」：AI 生成短片，第 2–8 週已上線。

  換影片時三種都要保留原本的位置與格式。
