# tempo-term mockups

[mukiwu/tempo-term](https://github.com/mukiwu/tempo-term) 的設計稿與互動原型。

**→ [yw-chan.github.io/tempo-term-mockups](https://yw-chan.github.io/tempo-term-mockups/)**

GitHub 不渲染 HTML，所以直接點 repo 裡的檔案只會看到原始碼。用上面那個網址看。

每一份都是自給自足的單一 HTML，沒有建置步驟；外部只依賴 Google Fonts，離線開會退回系統字型。圖形不是畫的，是跑真實演算法算出來的——lane 配置、配色、彎折路徑都是 `graphLayout.ts` 的規則移植過來的 JS。

## Git Graph 的 lane 幾何

| | |
|---|---|
| [Lane 預算](https://yw-chan.github.io/tempo-term-mockups/lane-budget-mockups.html) | `maxLane = 5` 為什麼是個問題，以及各家 git 工具的處理策略 |
| [欄寬階梯](https://yw-chan.github.io/tempo-term-mockups/lane-ladder-mockups.html) | 三段式解法，附可調參數 |
| [抖動測試台](https://yw-chan.github.io/tempo-term-mockups/lane-jitter-mockups.html) | 分頁載入時已畫好的列會不會換欄位 |

## 其他

| | |
|---|---|
| [未提交變更那一列](https://yw-chan.github.io/tempo-term-mockups/uncommitted-node-mockups.html) | issue #399 |
| [比較對象選擇器](https://yw-chan.github.io/tempo-term-mockups/fig-view-target.html) · [選單](https://yw-chan.github.io/tempo-term-mockups/fig-398-menu.html) | issue #398 |
| [早期設計稿](https://yw-chan.github.io/tempo-term-mockups/mockups.html) · [Issue 用設計稿](https://yw-chan.github.io/tempo-term-mockups/issue-mockups.html) | 合輯 |

---

這些是設計探索，不是規格書。有些方案的結論是「評估過、不做」，理由寫在各頁裡。
