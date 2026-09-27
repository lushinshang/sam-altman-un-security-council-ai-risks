# 當 AI 公司執行長走進安理會

## 簡介

2026 年 9 月 23 日，聯合國安理會由輪值主席國法國召集，邀請 OpenAI 執行長 Sam Altman、Anthropic 執行長 Dario Amodei、Hugging Face 共同創辦人 Clément Delangue 簡報 AI 風險，隨後近 20 位理事國與其他成員國代表相繼發言（另有 DeepSeek、Moonshot AI 代表與 Yoshua Bengio 據報也出席發言，但不在本文所依據的逐字稿片段內，詳見文中誠實標註）。本篇深度導讀梳理整場近兩個半小時的會議：導火線（Hugging Face 遭 OpenAI 自主代理入侵事件）、三位企業執行長各自的核心關切、法國提出的治理框架、各國在「全球監管 vs 國家主權」「開源 vs 封閉」「安理會職權」三條裂痕上的立場分佈、全球南方國家（索馬利亞、剛果民主共和國、哥倫比亞、巴拿馬）提出的關鍵批判，並更新了會議後三個月內的具體後續發展：METR 獨立調查、美國跨黨派國會調查、OpenAI 新模型 Astra 爭議、產業界「Pacing the Frontier」聯署信，以及網路社群的懷疑論調。

**修訂記錄**：2026-09-27 第二版——依 `codex exec` 套用 `ai-mentor-agents`／`is-mentor`／`editor-in-chief` 三個 skill 視角審查後修正多處事實與敘事問題（IAEA 成立年份、事件因果簡化、GLM-5.2 角色誇大等），並補充近三個月的後續事件與網路評論。

## 檔案清單

- `sam-altman-un-security-council-ai-risks.md` — 正式繁體中文深度導讀（Markdown）
- `index.html` — 發布就緒 HTML（雙擊即可用瀏覽器開啟，無需建置流程）
- `images/cover-16x9.png` — 封面概念圖（1664×936，16:9，AI 生成插畫，無文字/標誌）
- `images/hf-timeline.png` + `-mobile.png` — Hugging Face 事件完整時間軸資訊圖
- `images/governance-fault-lines.png` + `-mobile.png` — AI 治理三條裂痕比較圖
- `images/three-ceos-fears.png` + `-mobile.png` — 三位技術巨頭立場對比圖
- `images/france-four-pillars.png` + `-mobile.png` — 法國治理四大支柱圖
- `images/global-south-demands.png` + `-mobile.png` — 全球南方三國訴求對比圖
- `qa/` — HTML 驗收紀錄（結構、桌面/手機截圖、功能、無障礙、外部連結檢查）
- `research/` — 逐字稿完整整理、來源查證帳本、圖像提示詞、工作流程紀錄（僅本機保留）

## 原始資料

- **類型**：YouTube 影片逐字稿（自動字幕，非官方逐字稿）
- **標題**：LIVE: Sam Altman, AI Chiefs Brief UN Security Council on Risks From Artificial Intelligence | APT
- **網址**：https://www.youtube.com/watch?v=F-2O7VTcW4g
- **本機逐字稿位置**：`transcription/LIVE_Sam_Altman,_AI_Chiefs_Brief_UN_Security_Council_on_Risks_From_Artificial_Intelligence__APT_F-2O7VTcW4g.srt`（專案根目錄下）
- **字幕品質提醒**：YouTube 自動辨識字幕（`en-orig`），非會議官方逐字稿；人名、專有名詞經 agy 完整讀取後人工核對過主要講者身份，但無法排除少數細節的辨識誤差

## 最重要的官方、第一手及補充來源

- OpenAI 官方：[The Hugging Face incident and the road ahead](https://openai.com/index/hugging-face-incident-and-the-road-ahead/)
- Anthropic 官方：[Claude discovers a novel enzyme system with CRISPR-like repeats](https://www.anthropic.com/news/claude-discovers-novel-enzyme-system)
- Hugging Face 官方技術時間軸：[Anatomy of a Frontier Lab Agent Intrusion](https://huggingface.co/blog/agent-intrusion-technical-timeline)
- 白宮／美國商務部：[G20 Innovation Ministerial Concludes with Consensus Statement](https://www.whitehouse.gov/releases/2026/09/g20-innovation-ministerial-concludes-with-consensus-statement/)
- 維基百科：[World Artificial Intelligence Cooperation Organization](https://en.wikipedia.org/wiki/World_Artificial_Intelligence_Cooperation_Organization)
- METR：[獨立調查 Hugging Face 事件](https://metr.org/blog/2026-08-26-openai-hugging-face-incident-investigation/)
- Hawley 參議員辦公室：[國會調查 OpenAI 聲明](https://www.hawley.senate.gov/chairman-hawley-launches-investigation-into-openai-for-hacking-existential-risk-of-ai-products/)
- 完整來源清單見文章末尾與 `research/source-ledger.md`

## 狀態

**已發布。** 依專案既有慣例（一篇一個獨立 GitHub repo），本機已初始化獨立 `.git`，只提交 `.gitignore`／`README.md`／`sam-altman-un-security-council-ai-risks.md`／`index.html`／`images/`，`qa/` 與 `research/` 依規則不公開。

- Repo：https://github.com/lushinshang/sam-altman-un-security-council-ai-risks
- 網頁（GitHub Pages）：https://lushinshang.github.io/sam-altman-un-security-council-ai-risks/
- 發布日期：2026-09-27（後續補充 3 張段落資訊圖表）
