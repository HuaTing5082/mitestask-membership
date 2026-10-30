# 野蟎任務 訂閱制會員介紹頁

正式網址：https://member.mitestask.com.tw/

部署到 Railway：
1. Railway → New Project → Deploy from GitHub repo → 選這個 repo，會自動執行 npm start。
2. 服務的 Settings → Networking：Generate Domain 先測試；Custom Domain 輸入 member.mitestask.com.tw，依畫面指示到網路中文 DNS 新增 CNAME（和驗證用的 TXT）。
3. 若改用其他網址，請把 index.html 裡的 og:url、og:image 換成新網址，LINE / Facebook 分享預覽圖才會正常。

修改內容：直接編輯 index.html；分享預覽圖為 og-image.png（1200×630，檔名不變）。
