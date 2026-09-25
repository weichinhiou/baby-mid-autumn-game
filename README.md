# 寶寶過中秋

手機與電腦都能玩的中秋接物小遊戲。直接拖動戴兔耳帽的寶寶，接月餅和柚子得分，接熟烤串增加時間；避開炸彈、焦烤串和未熟烤串。

## 試玩

[立即開始遊戲](https://weichinhiou.github.io/baby-mid-autumn-game/)


下載本儲存庫後，直接用瀏覽器開啟 `index.html`。遊戲不需要帳號、資料庫或建置指令。

## GitHub Pages

在本儲存庫的 **Settings → Pages → Build and deployment** 選擇 **Deploy from a branch**，分支選 `main`，資料夾選 `/(root)`，按 **Save**。發布後網址為 `https://<你的 GitHub 帳號>.github.io/<儲存庫名稱>/`。

所有 WebP 必須與 `index.html` 位於同一目錄，並保持檔名不變。從專案路徑發布時，圖片仍會正常載入，因為程式使用相對路徑。

## 規格

完整玩法、物件機率、計分、時間和驗收情境，請見 [GAME_DESIGN.md](GAME_DESIGN.md)。

遇到圖片載入慢、舊版 iOS 顯示異常或音效無法恢復時，可先參考[踩坑紀錄與跨專案檢查清單](LESSONS_LEARNED.md)。

## 注意

此遊戲不儲存成績，也沒有排行榜。遊戲在瀏覽器執行；重新整理會重設分數。公開 GitHub 儲存庫中的程式和圖片對所有人可見。
