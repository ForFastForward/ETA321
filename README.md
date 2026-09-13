# ETA321 Public Website

這個 repository 存放 ETA321 的公開網站、App Store 支援頁面及條款及聲明。

網站首頁由 [index.html](index.html) 提供；啟用 GitHub Pages 後，網站網址預期為：

```text
https://forfastforward.github.io/ETA321/
```

## ETA321 是甚麼？

ETA321 是一個香港公共交通 ETA 應用程式，將港鐵、城巴及九巴公開 ETA 資料整理成穩定、易讀的分秒預估倒數，並支援路線地圖及 Live Activity。

到站時間及分秒倒數只屬預估資訊，並非營辦商提供的官方秒級保證。請以營辦商官方公告及現場資訊為準。

## Repository 結構

| 檔案 | 用途 |
| --- | --- |
| [index.html](index.html) | GitHub Pages 公開網站首頁。 |
| [terms-of-use.htm](terms-of-use.htm) | 使用條款。 |
| [data-privacy-policy.htm](data-privacy-policy.htm) | 私隱政策。 |
| [disclaimer.htm](disclaimer.htm) | 免責聲明。 |

## GitHub Pages

在 repository 的 **Settings → Pages**，選擇：

```text
Source: Deploy from a branch
Branch: main
Folder: /(root)
```

GitHub Pages 會使用根目錄的 `index.html` 作公開網站首頁。

## 資料來源與使用權限

ETA321 使用經 DATA.GOV.HK 發布的公開交通資料，並受其使用條款及適用資料集條件約束。

- [港鐵即時列車資料](https://data.gov.hk/en-data/dataset/mtr-data2-nexttrain-data) — 知識產權權利人：MTR Corporation Limited
- [九巴即時到站資料](https://data.gov.hk/en-data/dataset/hk-td-tis_21-etakmb) — 經運輸署發布；原始資料權利人包括 The Kowloon Motor Bus Company (1933) Limited 及 Long Win Bus Company Limited
- [城巴即時到站資料](https://data.gov.hk/en-data/dataset/ctb-eta-transport-realtime-eta) — 知識產權權利人：Citybus Limited
- [DATA.GOV.HK 使用條款及條件](https://data.gov.hk/tc/terms-and-conditions)

ETA321 為獨立開發的資訊工具，並非港鐵、九巴、城巴、DATA.GOV.HK 或任何營辦商的官方服務，亦不代表獲其認可。公開資料的使用不授予任何營辦商商標、標誌、官方網站內容或 API 規格文件的使用權。

## 更新網站

在本機的 `github_public` 資料夾修改檔案後，執行：

```bash
git add .
git commit -m "Describe your change"
git push
```

GitHub Pages 通常會在推送後數分鐘內重新部署網站。

## 聯絡與回饋

請透過 [GitHub Issues](https://github.com/ForFastForward/ETA321/issues) 提供測試意見或提出問題。GitHub Issues 可公開檢視，請勿張貼個人資料、位置資料或其他敏感內容。
