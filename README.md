# 紫微斗數排盤程式（Ziwei Chart）

一套以單一 HTML 檔打造的紫微斗數排盤工具。純前端、免安裝、免伺服器，開啟即可排盤，所有運算都在使用者瀏覽器本機端完成。

## 功能特色

- 支援**國曆（陽曆）／農曆（陰曆）**輸入，含閏月處理
- 出生時辰自動對應十二時辰（含早子／晚子）
- 排出**十二宮**、**十四主星**、**四化（祿權科忌）**、五行局、生肖
- 流年／流月運勢與飛星
- 一鍵**列印／存 PDF**
- 純前端、**離線可用**：出生資料不上傳、不儲存

## 檔案結構

| 檔案 | 說明 |
|------|------|
| [`ziwei/index.html`](ziwei/index.html) | 主程式（介面 + 排盤邏輯） |
| [`ziwei/iztro.min.js`](ziwei/iztro.min.js) | 排盤引擎（自架，iztro@2.5.1，MIT） |
| [`ziwei/legal.html`](ziwei/legal.html) | 免責聲明與隱私政策 |
| [`ziwei/THIRD-PARTY-LICENSES.md`](ziwei/THIRD-PARTY-LICENSES.md) | 第三方授權聲明 |
| [`ziwei/verification.md`](ziwei/verification.md) | 排盤精準度驗證報告 |

## 使用方式

1. 用瀏覽器直接開啟 `ziwei/index.html`（可雙擊、或用 `file://`，免架伺服器）
2. 選擇性別、曆法、出生日期與時間 → 點「開始排盤」
3. 需要時點「列印 / 存 PDF」輸出命盤

> 排盤引擎已改為本地載入，離線也能正常使用。

## 排盤引擎

排盤核心採用開源專案 [iztro](https://github.com/SylarLong/iztro)（MIT License），已自架於 `ziwei/iztro.min.js`，並保留 CDN 備援。授權詳見 [`THIRD-PARTY-LICENSES.md`](ziwei/THIRD-PARTY-LICENSES.md)。

## 授權與聲明

- 本專案自製之介面、版面與運勢評分文案，著作權歸作者所有。
- 內含之第三方元件依其原始授權（iztro 為 MIT）。
- 使用前請詳閱 [`legal.html`](ziwei/legal.html)：排盤結果**僅供參考**，不構成任何專業建議。

## 隱私

所有計算皆在使用者瀏覽器本機端完成，**出生日期、時辰與性別不會上傳或儲存**。
