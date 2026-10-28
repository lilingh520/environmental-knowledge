# 環境知識每日挑戰

開啟 `index.html` 即可使用，不需要伺服器或額外套件。

目前網站只使用 `question-bank.csv`，不再讀取 Google 雲端題庫。更新題庫時，替換同名 CSV 檔案後重新提交並推送即可。

## CSV 欄位

目前題庫使用以下欄位：

```text
級別,題目,選項1,選項2,選項3,選項4,答案,解析
```

網站也支援標準欄位 `category,question,optionA,optionB,optionC,optionD,answer,explanation`。答案可填 `A`、`B`、`C`、`D`，或填 1、2、3、4。

## 功能

- 每天依臺灣日期固定抽取 40 題。
- 送出後顯示分數、錯題、正確答案與詳解。
- 支援手機、平板與桌機響應式版面。
- 內建題庫作為 CSV 讀取失敗時的備援。
