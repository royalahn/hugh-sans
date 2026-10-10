<div align="right">
  🌐 <a href="README.md">English</a> | <b>한국어</b>
</div>

<div align="center">
  <a href="https://github.com/royalahn/hugh-sans">
    <img src="assets/rabbit.png" alt="Hugh Sans Mascot" width="220" />
  </a>

  <br />
  <br />

  <h1>Hugh Sans</h1>

  <p>
    <strong>구글 산스의 감성을 그대로, 윈도우와 웹을 위한 완벽한 행간 패치.</strong><br />
    줄바꿈 시 비정상적으로 벌어지던 2.4배 행간 버그를 타이포그래피 표준(1.25배)으로 해결했습니다.
  </p>

  <p>
    <a href="https://github.com/royalahn/hugh-sans/stargazers"><img src="https://img.shields.io/github/stars/royalahn/hugh-sans?style=for-the-badge&logo=github&color=18181b" alt="GitHub Stars" /></a>
    <a href="https://www.jsdelivr.com/package/gh/royalahn/hugh-sans"><img src="https://img.shields.io/badge/CDN-jsDelivr-E32B2B?style=for-the-badge&logo=jsdelivr&logoColor=white" alt="jsDelivr" /></a>
    <a href="css/hugh-sans.css"><img src="https://img.shields.io/badge/WOFF2-Optimized-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white" alt="WOFF2" /></a>
    <a href="OFL.txt"><img src="https://img.shields.io/badge/License-OFL_1.1-34A853?style=for-the-badge" alt="License: OFL-1.1" /></a>
  </p>

  <p>
    <a href="#-웹-폰트-사용법-jsdelivr-cdn"><b>웹폰트 사용법</b></a> &bull;
    <a href="#-수정-사항-patch-notes"><b>수정 내용</b></a> &bull;
    <a href="#-포함된-글꼴-목록"><b>글꼴 다운로드</b></a> &bull;
    <a href="README.md"><b>English</b></a>
  </p>
</div>

---

## 🔍 수정 사항 (Patch Notes)

* **윈도우 메트릭 정상화**:
  * 기존 Google Sans의 `usWinAscent(1323)` 및 `usWinDescent(1079)` 합계(2402, 약 240%)로 인해 윈도우 기본 렌더러(GDI, 메모장 등)에서 줄바꿈 시 비정상적으로 넓게 벌어지던 행간을 `sTypo` 메트릭과 동일한 **1252 (125.2%)**로 수정하였습니다.
  * `usWinAscent`: `1323` ➔ **`966`**
  * `usWinDescent`: `1079` ➔ **`286`**
* **메타데이터 및 라이선스 준수**:
  * SIL Open Font License 1.1 및 상표권 규정에 따라 폰트 패밀리 명칭을 **Hugh Sans**로 변경하였습니다.

---

## 🚀 웹 폰트 사용법 (jsDelivr CDN)

HTML `<head>`에 아래 스타일시트를 추가하거나 CSS 파일 상단에 `@import`하여 사용할 수 있습니다.

### HTML
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/royalahn/hugh-sans@latest/css/hugh-sans.css" />
```

### CSS
```css
@import url('https://cdn.jsdelivr.net/gh/royalahn/hugh-sans@latest/css/hugh-sans.css');

body {
  font-family: 'Hugh Sans', sans-serif;
}
```

> **Tip:** 배포 안정성을 위해 `@latest` 대신 특정 브랜치(`@main`)나 GitHub 릴리스 태그(`@v1.0.0`)를 지정하여 사용하는 것을 권장합니다.
> 예: `https://cdn.jsdelivr.net/gh/royalahn/hugh-sans@main/css/hugh-sans.css`

---

## 📦 포함된 글꼴 목록

### Desktop (TTF)
* `fonts/ttf/HughSans-Regular.ttf` (Weight: 400)
* `fonts/ttf/HughSans-Medium.ttf` (Weight: 500)
* `fonts/ttf/HughSans-SemiBold.ttf` (Weight: 600)
* `fonts/ttf/HughSans-Bold.ttf` (Weight: 700)

### Web Font (WOFF2)
* `fonts/woff2/HughSans-Regular.woff2` (Weight: 400)
* `fonts/woff2/HughSans-Medium.woff2` (Weight: 500)
* `fonts/woff2/HughSans-SemiBold.woff2` (Weight: 600)
* `fonts/woff2/HughSans-Bold.woff2` (Weight: 700)

---

## 📄 라이선스 (License)

이 폰트는 [SIL Open Font License, Version 1.1](OFL.txt)에 따라 배포됩니다.
자세한 내용은 [OFL.txt](OFL.txt)를 참조하세요.
