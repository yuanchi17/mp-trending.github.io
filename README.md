# 微程式資訊股份有限公司 創新前瞻計畫室 純靜態網站

* 網址: <https://campagin.program.com.tw>

## 開發環境架設

```bash
git clone git@github.com:mp-trending/mp-trending.github.io.git
cd mp-trending.github.io
cp example.env .env
yarn
yarn dev
```

* 開發環境預設網址: <https://localhost:3000>
* 開發環境是自簽署憑證，若使用 Google Chrome 可輸入 `thisisunsafe` 跳過

## GitHub Action 設定 (正式站)

* `Secret`

```
BASEURL=
CNAME=
LIFFID_FULL=
```
