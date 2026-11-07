# F-PC-zh-tw — F-PC Forth 文獻保存庫（原文 + 繁體中文教材）

本庫是 **F-PC Forth** 相關文獻的**保存性典藏（preservation archive）**：保留原始文件，
以及臺灣符式社群多年來留下的繁體中文（zh-TW）翻譯與教材，讓以後想研究 Forth、
F-PC 內部運作或 8086 組合語言教學的人有個依據。

> **緣起**：2026 年 11 月，靜宜大學退休榮譽教授金城老師（燾昍）尋找當年 8086 組合語言
> 課上「用 F-PC 的 Forth 組譯／反組譯 8086 組語」的講義，想提供給正在教 8086 組語的
> 鄧淵元老師。搜尋過程發現這批 1980–90 年代文獻在網路上四散、部分來源已不穩定，
> 因此集中典藏於此。

## 目錄結構

```
originals/                  原始文件（PDF / ZIP 原樣保存）
eforth-academy-f-pctech/    易符學苑《F-PC Technical Reference Manual》線上 HTML 版全文
zh-tw/                      繁體中文翻譯與教材（臺灣符式推廣協會網頁原樣快照）
```

## 典藏內容

### 原始文件（`originals/`）

| 檔案 | 內容 | 來源 |
|---|---|---|
| `FPC36.ZIP` | F-PC 3.6 完整發行版（1994，Tom Zimmer）— 系統、原始碼、文件 | forth.org「Public Domain Forths」頁 |
| `F-PC-main.zip` | [uho/F-PC](https://github.com/uho/F-PC) 儲存庫快照（2021-03-26），含 F-PC.EXE 與完整原始碼、Docker/DOSEMU 啟動腳本 | GitHub uho/F-PC |
| `F-PC_Technical_Reference_Manual_1989.pdf` | 《F-PC 3.5 Technical Reference Manual》第二版（C.H. Ting，1989-11，291 頁） | FIG 保存原件轉製 PDF |
| `F-PC_Technical_Reference_Manual.pdf` | 同上內容的網頁版合成 PDF（452 頁）— 由本庫自易符學苑 HTML 章節合併轉檔製作 | eforth.com.tw HTML 版 |
| `Real-Time-Forth-v5.pdf` | Tim Hendtlass《Real Time Forth》（265 頁），PASM 組譯器與 8086 反組譯實作教學 | 社群公開散佈版 |
| `TheZenOfForth.pdf` | 金城（愛新覺羅・燾昍）編著《FORTH 的禪思》電子書（362 頁） | 作者授權製作之電子書 |
| `FD-V04N6.pdf` | Forth Dimension Vol. IV No. 6 —「Teaching Forth」專輯（Vernor Vinge 等） | forth.org 公開掃描 |
| `FD-V13N1.pdf` | Forth Dimension Vol. XIII No. 1 | forth.org 公開掃描 |
| `FD-V17N4.pdf` | Forth Dimension Vol. XVII No. 4 | forth.org 公開掃描 |

### 易符學苑 HTML 版（`eforth-academy-f-pctech/`）

丁陳漢蓀博士親自在 [易符學苑 eForth Academy](https://eforth.com.tw/academy/library/f-pctech.htm)
公開的《F-PC Technical Reference Manual》全文，共 9 個檔案（目錄 + 8 章）：
虛擬機器、Kernel、輸入輸出與數值、直譯器與編譯器、系統初始化、Kernel 工具、
基礎工具（一）（二）。`f-pctech.htm` 為原站目錄頁。

### 繁體中文教材（`zh-tw/`）

原樣快照自 [臺灣符式推廣協會 FigTaiwan](https://sites.google.com/site/figtaiwanfigtaiwan/)
（Google Sites），含瀏覽器存檔的 `_files` 資產資料夾，下載後離線開啟可正常顯示：

| 檔案 | 內容 |
|---|---|
| `臺灣符式推廣協會 FigTaiwan - 第壹篇 入門篇.html` | F-PC 自學手冊繁中化教材（1992–93 年靜宜大學時期中文化工作之延續），涵蓋安裝、入門與 F-PC 內建組譯／反組譯程式之使用 |
| `臺灣符式推廣協會 FigTaiwan - 易符建制 eForth 2.0 implementation.html` | 易符 eForth 2.0 implementation 說明文件 |

## 版權狀態

逐項查證結果（詳細來源 URL 與查證日期見 [PROVENANCE.md](PROVENANCE.md)）：

- **F-PC 系統與其隨附文件**（`FPC36.ZIP`、`F-PC-main.zip`）：**Public Domain** —
  列於 FIG 官方 [Public Domain Forths](https://www.forth.org/eforth.html) 頁面，可自由散佈。
- **《Real Time Forth》**：書中版權頁明示以 **shareware** 方式發行 —
  「可自由拷貝給他人使用，惟不得營利」→ 散佈經作者明文允許。
- **《FORTH 的禪思》**：書首版權聲明明示「本電子書的出現乃是為了推廣 FORTH，
  **歡迎各界人士拷貝傳閱**」→ 散佈經作者明文允許。
- **《F-PC Technical Reference Manual》**：© 1989 C.H. Ting（丁陳漢蓀，1939–2022）。
  作者生前將全文免費公開於自己的易符學苑網站，2013 年亦曾授權 FIG 數位典藏
  Offete 出版品 → 屬作者授權之公開散佈，版權仍歸權利人。
- **Forth Dimension 各期**：© Forth Interest Group 及各文作者；FIG 社群長期在
  [forth.org](https://www.forth.org/fd/) 公開提供全部各期掃描 → 屬出版方社群之公開散佈。
- **FigTaiwan 教材**：臺灣符式推廣協會官網公開之教育教材，版權歸協會與原作者。

## 權利聲明

本庫為**保存與教育目的**之典藏，不主張任何上述文件之權利；所有權利歸屬各原作者、
譯者與出版者。各檔案依其原始授權條件散佈（見上）。

若您是權利人且認為任何檔案不應出現於此，請開 issue 或聯絡庫主，我們會儘速移除。

## 相關資源

- [易符學苑（eForth Academy）](https://eforth.com.tw/) — 丁陳漢蓀博士的 Forth 文獻庫
- [Forth Interest Group（FIG）](https://www.forth.org/) — Forth Dimensions 全卷、Public Domain Forths
- [uho/F-PC](https://github.com/uho/F-PC) — F-PC 3.6 可執行安裝（Docker/DOSEMU）
- [臺灣符式推廣協會 FigTaiwan](https://sites.google.com/site/figtaiwanfigtaiwan/) — 官方 Google Sites
