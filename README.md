# 11月英文複習

給小孩在 iPad 上用的英文練習頁。單一檔案 `index.html`，無外部資源，iPad 白名單只需 `ningchencontact.github.io`。

## 內容

分頁切換三組進度：

- **學校 Unit 3**：pen、pencil、marker、eraser、book、ruler；Is this your pencil?；主詞與所有格
- **安親班 Unit 3**：watch a movie 等四個片語；He's / He isn't / They're / They aren't
- **安親班 Unit 4**：sandwich、hot dog、soup、pancake、juice；What day…?；has / have、doesn't / don't、some / any

每組四種練習：單字、句型、縮寫、紙上聽寫。縮寫是重點（補撇、長短式互換、找錯、They're / Their / There）。

規則：每回 5 題；少於 2 秒就按不算分；第一次答錯先給提示再試一次，**重試時選項、字卡位置不變**；不用紅色。進度存在該台 iPad，localStorage 前綴 `kid2_nov_`。

## 如何更新

1. 編輯 `index.html`：題庫在 `學校 Unit 3`、`安親班 Unit 3`、`安親班 Unit 4` 三個區塊，改文字即可。新單元請複製區塊並加進 `UNITS`。
2. 用瀏覽器開啟，每個單元各做一回確認。
3. 推到 main：

   ```
   git add index.html
   git commit -m "更新題庫"
   git push origin main
   ```
4. 等 GitHub Pages 更新約 1～2 分鐘，iPad 重新整理。

亂按秒數改檔案開頭的 `TOO_FAST`（毫秒）。
