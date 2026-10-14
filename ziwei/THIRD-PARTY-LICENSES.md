# 第三方元件授權聲明（Third-Party Licenses）

本專案（紫微斗數排盤）使用下列第三方開源元件。**商用或對外散布時，請保留本檔與各元件的授權聲明。**

> **離線聲明**：本專案已完全離線化，頁面不載入任何 CDN 或外部資源。早期版本曾使用 `es-module-shims` 與 `esm.sh` / `esm.run` / `jsDelivr`（皆為 iztro 的 CDN 備援），現已全部移除；目前唯一的第三方執行期元件為本地自架之 `iztro.min.js`。

---

## iztro（紫微斗數排盤引擎）

- 用途：紫微斗數排盤核心引擎
- 版本：2.5.1
- 原始專案：<https://github.com/SylarLong/iztro>
- 官方網站／文件：<https://iztro.com>
- 授權條款：**MIT License**
- 本專案散布形式：本地自架 `iztro.min.js`（`ziwei/iztro.min.js`）

### MIT License 全文

```
MIT License

Copyright (c) 2023 All Contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

> 備註：`iztro` 以 MIT 授權釋出，**允許商業使用、修改與再散布**，條件是保留上述著作權與授權聲明。本專案已將引擎自架於本地（`ziwei/iztro.min.js`），並在**該檔開頭內嵌 MIT 授權與著作權聲明**，同時於本檔保留全文，以符合 MIT「聲明須隨所有副本或實質部分散布」之要求。本專案**不使用任何 CDN**，亦不連線任何外部伺服器。

---

## 字型

- **Noto Serif TC**（Google Noto 系列）：以 SIL Open Font License 1.1 釋出，允許商業使用。
- **Microsoft JhengHei**：為系統內建字型。

> 本專案目前**僅以 CSS `font-family` 引用**上述字型，**未內嵌或散布任何字型檔**，因此不觸發各字型授權的散布義務。若未來改為自架（自帶 `.woff2` 等字型檔），須一併附上各字型的授權全文與著作權聲明；Noto 系列另受 SIL OFL 之「保留字型名稱（Reserved Font Name）」條款限制，修改字型時須更名。

---

## 紫微斗數傳統知識

十二宮、十四主星、四化（祿權科忌）、天干地支等屬流傳久遠之傳統知識，不受著作權保護。本專案自行撰寫的版面、文案與運勢評分規則，著作權歸本專案所有。
