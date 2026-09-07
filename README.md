# B-TV-page — 感應光寓 · TV 主顯示（白版預覽）

寶舖大安段策展 B 區「感應光寓」客廳 TV 主顯示的**建置產物預覽**，只放 `vite build` 的輸出，
不含原始碼。原始碼在私有的 [VistwinProject/B-TV](https://github.com/VistwinProject/B-TV)（`main` = 白版）。

- 預覽：<https://vistwinproject.github.io/B-TV-page/>
- 機位設定工具：`camera-tool.html`

## 擋搜尋

這個 repo 是 public（GitHub Pages 需要），但頁面本身不希望被搜尋到：

- `index.html` 與 `camera-tool.html` 都有 `<meta name="robots" content="noindex, nofollow">`
- `robots.txt` 為 `User-agent: * / Disallow: /`

## 操作

| 鍵 | 動作 |
|---|---|
| `i` / `Enter` | 開始（前言） |
| `n` / `→` | 下一步 |
| `o` | 結語 |
| `r` / `Esc` | 回待機 |
| `c` | 模擬刷邀請卡 |
| `1`–`5` | 模擬刷情境鑰匙圈 |
| `x` / `Space` | 模擬拿起 |
| `e` | 佈展編輯模式（配色 / 版面） |

展場實機由 NFC 讀卡機（`ws://localhost:8788`）驅動，此預覽無讀卡機，右下角會顯示「連線中」，用鍵盤操作即可。
