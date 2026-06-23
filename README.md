# PFJ 美富紅盈 — 富邦人壽試算

富邦人壽美富紅盈外幣分紅終身壽險（PFJ）試算頁。

## 使用

直接開啟 `index.html` 即可試算；也可整包上傳 GitHub Pages。`index.html` 已內嵌 config + tables，因此本機雙擊也能使用。

## 驗證

Excel cached case：女 25 歲、6 年期、10 萬美元、中分紅。

- 折扣後年繳保費：7247
- 年 1 身故金 / 解約金：21000 / 2670
- 年 6 身故金 / 解約金：300215 / 44808
- 年 86 身故金 / 解約金：621047 / 621047
- 驗證：1118 / 1118 cells matched

## 結構

```
index.html
products/PFJ/config.json
products/PFJ/tables.json
favicon/
favicons/
tools/
```
