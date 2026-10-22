# card-duel

卡牌對戰遊戲的可玩原型（單一 `index.html`，原生 JS，手機直式可玩、桌機自動改成左右兩欄）。

## 玩法
直接用瀏覽器打開 `index.html`，或開 GitHub Pages 網址：
`https://dan0618x.github.io/card-duel/`

## 調數字
所有卡牌、角色、數值都在 `index.html` 最上面的 `CONFIG` 物件，改完重新整理即可。

## GitHub Pages 設定（一次性）
1. Repo → **Settings → Pages → Build and deployment → Source** 選 **GitHub Actions**
2. 把程式合併到 `main`，`.github/workflows/pages.yml` 會自動部署（也可以在 Actions 頁手動執行）

不想合併的話，也可以把 Source 改成 **Deploy from a branch**，選這個分支、資料夾 `/ (root)`。
