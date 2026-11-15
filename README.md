# 信心之旅：直到晨光來臨（測試版）

這個資料夾是**已經建置好的單人測試版網頁**，整包上傳到 GitHub 就能用 GitHub Pages 開啟。

- 只有單人；沒有連線伺服器，所以沒有同行。
- 遊玩紀錄不會被保存。
- 原始碼不在這裡，在 `faith-journey` 資料夾。這裡的檔案是由原始碼產生的，不要直接修改。

重新產生（在 `faith-journey` 資料夾裡）：

```bash
VITE_BASE=./ VITE_TEST_BUILD=solo npm run build
```

產生的檔案在 `apps/client/dist/`，用它取代這個資料夾的內容。
