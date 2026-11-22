# 氣牆玄學法科 — 靜態網站

香港繁體中文、跑在瀏覽器即開即用嘅 5 頁靜態網站，無需後端、無需安裝。

## 頁面
- `index.html` — 首頁（Hero＋服務概述）
- `services.html` — 法科服務（收費項目同做法流程）
- `qi-wall.html` — 氣牆知識（識別訊號＋日常保養）
- `festivals.html` — 節令記事（拜神時節表＋升運貼士，2026/2027 公曆對照）
- `convert.html` — 新曆轉農曆（1901–2099 萬年曆換算工具頁）
- `testimonials.html` — 案例見證（化名個案）
- `contact.html` — 聯絡／約期
- `assets/style.css` — 全站樣式
- `assets/js/lunar.js` — 農曆萬年曆庫（lunar-javascript v1.7.8，本地內嵌，離線照用）

## 點開
直接雙擊任意 `index.html`，或喺資料夾開本地 server：
```bash
cd ~/Downloads/project1
python3 -m http.server 8000
# then open http://localhost:8000
```

## 聯絡資料（已填真實資料）
- Whatsapp／電話：`+852 9413 9151`（`tel:+85294139151`、WhatsApp `wa.me/85294139151` 都配好）
- 電郵：`samian4134@gmail.com`（mailto 已配好）
- 微信：暫時冇提供，頁面已移除該項——想加返隨時講

## 開舖前仍要注意
- 服務時間、地址、初一十五安排，`contact.html` 內仲係建議值，按實際改

## 設計
- 主題色：深墨底＋朱砂紅＋黃金，宣紙感字體，玄學／法科氛圍。
- 全部導覽互相連結，手機有響應式排列。
- 文中已加「誠信叮囑」同「禁止事項」，強調正法、唔硬撬、明碼實價。
