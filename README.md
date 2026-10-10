<div align="right">
  🌐 <b>English</b> | <a href="README_ko.md">한국어</a>
</div>

<div align="center">
  <a href="https://github.com/royalahn/hugh-sans">
    <img src="assets/rabbit.jpg" alt="Hugh Sans Mascot" width="650" />
  </a>

  <br />
  <br />

  <h1>Hugh Sans</h1>

  <p>
    <strong>The geometric typeface you love, fixed for Windows &amp; the Web.</strong><br />
    Fixes abnormal 2.4x line-spacing metrics while preserving the iconic Google Sans aesthetic.
  </p>

  <p>
    <a href="https://github.com/royalahn/hugh-sans/stargazers"><img src="https://img.shields.io/github/stars/royalahn/hugh-sans?style=for-the-badge&logo=github&color=18181b" alt="GitHub Stars" /></a>
    <a href="https://www.jsdelivr.com/package/gh/royalahn/hugh-sans"><img src="https://img.shields.io/badge/CDN-jsDelivr-E32B2B?style=for-the-badge&logo=jsdelivr&logoColor=white" alt="jsDelivr" /></a>
    <a href="hugh-sans.css"><img src="https://img.shields.io/badge/WOFF2-Optimized-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white" alt="WOFF2" /></a>
    <a href="OFL.txt"><img src="https://img.shields.io/badge/License-OFL_1.1-34A853?style=for-the-badge" alt="License: OFL-1.1" /></a>
  </p>

  <p>
    <a href="#-web-font-usage-jsdelivr-cdn"><b>Web Font</b></a> &bull;
    <a href="#-patch-notes"><b>Why Hugh Sans?</b></a> &bull;
    <a href="#-included-fonts"><b>Download Fonts</b></a> &bull;
    <a href="README_ko.md"><b>한국어 문서</b></a>
  </p>
</div>

---

## 🔍 Patch Notes

* **Windows Metric Normalization**:
  * In the original Google Sans font, the sum of `usWinAscent` (1323) and `usWinDescent` (1079) totaled **2402 (~240%)**. This caused native Windows text renderers (such as GDI, Notepad, etc.) to render excessively wide line spacing when breaking lines.
  * These values have been adjusted to match the standard typography (`sTypo`) metrics of **1252 (125.2%)**:
    * `usWinAscent`: `1323` ➔ **`966`**
    * `usWinDescent`: `1079` ➔ **`286`**
* **Metadata & License Compliance**:
  * In accordance with the SIL Open Font License 1.1 and Google LLC trademark policies, the font family has been renamed to **Hugh Sans**.

---

## 🚀 Web Font Usage (jsDelivr CDN)

You can load Hugh Sans directly via jsDelivr CDN by adding the stylesheet to your HTML `<head>` or `@import`ing it in your CSS.

### HTML
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/royalahn/hugh-sans@latest/hugh-sans.css" />
```

### CSS
```css
@import url('https://cdn.jsdelivr.net/gh/royalahn/hugh-sans@latest/hugh-sans.css');

body {
  font-family: 'Hugh Sans', sans-serif;
}
```

> **Tip:** For production stability, it is recommended to specify a branch (`@main`) or release tag (`@v1.0.0`) instead of `@latest`.  
> Example: `https://cdn.jsdelivr.net/gh/royalahn/hugh-sans@main/hugh-sans.css`

---

## 📦 Included Fonts

### Desktop (TTF)
* `HughSans-Regular.ttf` (Weight: 400)
* `HughSans-Medium.ttf` (Weight: 500)
* `HughSans-SemiBold.ttf` (Weight: 600)
* `HughSans-Bold.ttf` (Weight: 700)

### Web Font (WOFF2)
* `HughSans-Regular.woff2` (Weight: 400)
* `HughSans-Medium.woff2` (Weight: 500)
* `HughSans-SemiBold.woff2` (Weight: 600)
* `HughSans-Bold.woff2` (Weight: 700)

---

## 📄 License

This font software is licensed under the [SIL Open Font License, Version 1.1](OFL.txt).  
Please see [OFL.txt](OFL.txt) for details.
