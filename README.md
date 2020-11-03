# STUDY4 - Short URL App

A Short URL App base on github page.

若要增加短網址，請直接修改 `routes.json` 檔，以 `"key" : "value"` 的方式建立，`key` 為短網址名稱，`value` 為目標網址。

## 本機測試

這裡使用 [live-server](https://www.npmjs.com/package/live-server) 進行測試。

為了模擬 GitHub Page 找不到網頁時，會自動改用 `404.html` 開啟網頁，啟動 live-server 時，請加上 `--entry-file=404.html` 參數。

```bash
# 安裝 live-server 微型伺服器
npm install -g live-server
# 啟動 live-server 並指定找不到網頁時，使用 404.html 開啟網頁
live-server --entry-file=404.html
```
