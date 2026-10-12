# 他石智慧產權事務所 官網

單頁網站（單一 `index.html`，無建置流程），由 GitHub Pages 從 `main` 分支根目錄發佈：
https://shianshiu.github.io/timestone-preview/

## 檔案

| 路徑 | 用途 |
| --- | --- |
| `index.html` | 整個網站（HTML／CSS／少量 JS） |
| `img/seal-768.webp`、`img/seal-1536.webp` | 品牌照片（壓印紙卡） |
| `img/line-qr.jpg` | 業主提供的 LINE QR（電腦版顯示） |
| `img/og.jpg` | 分享預覽圖 1200×630 |
| `img/favicon.svg`、`img/apple-touch-icon.png` | 網站圖示 |
| `sitemap.xml` | 提交給 Google Search Console 用 |

## 聯絡資訊（改這裡時要全站一起改）

- 電話：`tel:0225238365`／`tel:+886225238365`
- LINE：`https://line.me/R/ti/p/Rbqbtlkq3p`（由 `img/line-qr.jpg` 解出；`/R/` 讓手機直接開加好友）。
  若改用 LINE 官方帳號，連結與 QR 圖要一起換。

## 換成正式網域時

把 `index.html` 的 canonical、`og:url`、`og:image`、JSON-LD 的 `url`／`image`，以及 `sitemap.xml` 裡的網址，
從 `https://shianshiu.github.io/timestone-preview/` 換成新網域，並在網域根目錄加 `robots.txt`。
