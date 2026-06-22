# 中盛工程有限公司 官方網站

純靜態網站（HTML / CSS / JS），可直接部署到 Vercel，免費、速度快、SEO 友善。

## 檔案結構
```
zhongsheng-website/
├─ index.html      # 網站主頁（所有內容＋SEO 標籤＋結構化資料）
├─ styles.css      # 樣式
├─ script.js       # 行動版選單、年份
├─ robots.txt      # 允許搜尋引擎收錄
├─ sitemap.xml     # 網站地圖（給 Google）
└─ images/         # 工程實績照片（image1～image12）
```

## ⚠️ 上線前必填（目前是佔位文字）
請把以下實際資料告訴我、或自行在 `index.html` 搜尋取代：

1. **電話 / 傳真 / Email / 地址** — 在「聯絡我們」區塊（搜尋「請提供」）。
2. **結構化資料** — `<script type="application/ld+json">` 內的 telephone / email / address，
   填好後 Google 才能在搜尋結果顯示你的電話與地圖。
3. **網域** — 把所有 `https://www.example.com.tw/` 換成正式網域。

## 部署到 Vercel
1. 到 https://vercel.com 用 Google 帳號登入。
2. 「Add New… → Project」→ 把整個 `zhongsheng-website` 資料夾拖進去（或連 GitHub）。
3. Framework 選「Other / 靜態」，直接 Deploy，幾秒後得到 `xxx.vercel.app` 網址。

## 讓 Google 搜尋得到（3 步）
1. **買網域**（建議 .com.tw 或 .com，年費約 NT$400–800），在 Vercel 專案
   Settings → Domains 綁定。
2. **Google Search Console**（https://search.google.com/search-console）
   → 新增資源 → 驗證網域 → 提交 `sitemap.xml`。
3. **Google 商家檔案**（Google Business Profile）登錄公司名稱、電話、地址，
   讓你在地圖與搜尋更容易被找到。

收錄通常需幾天到兩週。
