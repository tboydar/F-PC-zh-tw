# PROVENANCE — 來源與版權查證紀錄

每個典藏檔案的原始來源、抓取日期與版權狀態。抓取日期統一為 **2026-11-07**。

## originals/

| 檔案 | 大小 | 原始來源 | 版權狀態 | 依據 |
|---|---|---|---|---|
| `FPC36.ZIP` | 1.1 MB | forth.org — Public Domain Forths 頁面之 `fpc36.zip`（1994-12 發行） | Public Domain | 列於 FIG 官方 [Public Domain Forths](https://www.forth.org/eforth.html) 頁 |
| `F-PC-main.zip` | 1.0 MB | [github.com/uho/F-PC](https://github.com/uho/F-PC) 快照（2021-03-26），README 明言「for conservation, reference and experimentation」 | 內容為 Public Domain 之 F-PC 3.6 | 同上；該 repo 為社群保存性質 |
| `F-PC_Technical_Reference_Manual_1989.pdf` | 2.7 MB | FIG 保存之《F-PC 3.5 Technical Reference Manual》第二版（1989-11）原件轉製 PDF，291 頁，含章節書籤 | © 1989 C.H. Ting / Offete Enterprises；作者生前免費公開全文於易符學苑，並曾授權 FIG 數位典藏 Offete 出版品 | 版權頁「(c) Copyright 1989 by C. H. Ting」；[易符學苑公開全文](https://eforth.com.tw/academy/library/f-pctech.htm) |
| `F-PC_Technical_Reference_Manual.pdf` | 7.4 MB | 本庫自製：合併易符學苑 9 個 HTML 章節後以瀏覽器排版引擎轉製之 PDF（452 頁） | 內容同上；製作過程僅格式轉換 | 見 `eforth-academy-f-pctech/` |
| `Real-Time-Forth-v5.pdf` | 0.8 MB | 社群公開流傳之 Tim Hendtlass《Real Time Forth》v5，265 頁 | Shareware — 明文允許非營利拷貝散佈 | 書中版權頁：「This book has been written as shareware. You may make copies for your own use or to give to others provided that you do not make a profit thereby.」 |
| `TheZenOfForth.pdf` | 1.4 MB | 《FORTH 的禪思》電子書，金城（愛新覺羅・燾昍）編著，潘德喜謄打、王雨農轉 PDF，362 頁 | 作者明文允許拷貝傳閱，版權歸原作者 | 書首版權聲明：「本電子書的出現乃是為了推廣 FORTH，歡迎各界人士拷貝傳閱」 |
| `FD-V04N6.pdf` | 3.3 MB | Forth Dimension Vol. IV No. 6（Teaching Forth 專輯） | © FIG 及各文作者；出版方社群公開提供掃描 | [forth.org/fd](https://www.forth.org/fd/) 公開下載 |
| `FD-V13N1.pdf` | 8.0 MB | Forth Dimension Vol. XIII No. 1 | 同上 | 同上 |
| `FD-V17N4.pdf` | 8.3 MB | Forth Dimension Vol. XVII No. 4 | 同上 | 同上 |

## eforth-academy-f-pctech/

易符學苑《F-PC Technical Reference Manual》線上 HTML 版全文，抓取自
`https://eforth.com.tw/academy/library/f-pctech.htm` 及其 9 個章節連結
（章節檔名含 `\`，實際 URL 需以 `%5C` 編碼存取）：

| 檔案 | 對應章節 |
|---|---|
| `f-pctech.htm` | 原站目錄頁 |
| `contents.htm` | Prefaces and Contents |
| `virtualmachine.htm` | Ch.1 The F-PC Virtual Forth Machine |
| `f-pckernel.htm` | Ch.2 The F-PC Kernel |
| `inputoutputnumbers.htm` | Ch.3 Input, Output and Numbers |
| `interpretercompiler.htm` | Ch.4 Interpreter and Compiler |
| `systeminitiation.htm` | Ch.5 System Initiation |
| `kernelutilities.htm` | Ch.6 Kernel Utilities |
| `basicutilities.htm` | Ch.7 Basic Utilities（一） |
| `basicutilities2.htm` | Ch.7 Basic Utilities（二） |

版權狀態同 `F-PC_Technical_Reference_Manual_1989.pdf`（作者本人公開）。

## zh-tw/

原樣快照自臺灣符式推廣協會官方 Google Sites
（`https://sites.google.com/site/figtaiwanfigtaiwan/`），含瀏覽器存檔之 `_files`
資產資料夾以維持離線可讀。版權歸臺灣符式推廣協會與原作者。

| 檔案 | 內容 |
|---|---|
| `臺灣符式推廣協會 FigTaiwan - 第壹篇 入門篇.html`（+ `_files/`） | F-PC 自學手冊繁中化教材（1992–93 靜宜大學中文化工作之延續） |
| `臺灣符式推廣協會 FigTaiwan - 易符建制 eForth 2.0 implementation.html`（+ `_files/`） | 易符 eForth 2.0 implementation 說明 |

## 查證過程補充

- 丁陳漢蓀（Chen-Hanson Ting）生於 1939-08-29，卒於 2022-05-30（FIG 紀念頁）。
  其 Offete Enterprises 出版品 2013 年起經授權於 FIG 數位典藏。
- F-PC 為 Tom Zimmer 開發之 DOS Forth 系統，內建 PASM 組譯器與
  Charles Curley 之 8086 反組譯器（`CURLEY.ZIP`、`ZIMMER.ZIP` 含於 `FPC36.ZIP`）。
- 《Real Time Forth》第 18 章即為 PASM 組譯器與 8086 組語練習之教學，
  與金城老師回憶之 8086 課堂講義主題吻合（惟講義原件仍未尋獲）。
