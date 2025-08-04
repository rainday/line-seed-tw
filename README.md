# LINE Seed TW Webfont CDN (via GitHub + jsDelivr)

本專案提供 [LINE Seed TW 繁體字型](https://seed.line.me/index_tw.html) 的 CDN 快速存取方式，便於前端專案直接使用。

## 授權 License

本字型依據 [SIL Open Font License 1.1](https://scripts.sil.org/OFL) 免費自用及商用，可再分發。請勿販售原字型檔。

可參考[官方授權原文](https://seed.line.me/index_tw.html)。

## jsDelivr CDN 快速引用

#### 字體檔直接引用
```
@font-face {
  font-family: 'LINE Seed TW';
  src: url('https://cdn.jsdelivr.net/gh/rainday/line-seed-tw@main/fonts/LINESeedTW-Regular.woff2') format('woff2');
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}
```
text

#### 直接載入 CSS
```
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/rainday/line-seed-tw@main/css/lineseedtw.css">
```
使用方法
在你的CSS或HTML中引入上述 CDN 路徑。

套用：

```
body {
  font-family: 'LINE Seed TW', 'Noto Sans TC', sans-serif;
}
```
字體來源
LINE Seed TW 官方下載

授權標註：Built by LINE Corporation, licensed under OFL 1.1

注意事項
僅限於合法授權範圍內使用（商用、網頁、App均可）

若自行修改字體檔案，請保留原始授權，並註明修改
