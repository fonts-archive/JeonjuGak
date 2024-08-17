# 전주완판본 각체

[배포처 바로가기](https://www.jeonju.go.kr/index.9is?contentUid=9be517a75cfc1850015d0becebbf4672)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Jeonju Gak`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/JeonjuGak/JeonjuGak.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/JeonjuGak/JeonjuGak.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'Jeonju Gak';
    font-weight: 300;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/JeonjuGak/JeonjuGak-Light.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/JeonjuGak/JeonjuGak-Light.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/JeonjuGak/JeonjuGak-Light.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/JeonjuGak/JeonjuGak-Light.ttf') format('truetype');
}
@font-face {
    font-family: 'Jeonju Gak';
    font-weight: 400;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/JeonjuGak/JeonjuGak-Regular.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/JeonjuGak/JeonjuGak-Regular.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/JeonjuGak/JeonjuGak-Regular.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/JeonjuGak/JeonjuGak-Regular.ttf') format('truetype');
}
@font-face {
    font-family: 'Jeonju Gak';
    font-weight: 700;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/JeonjuGak/JeonjuGak-Bold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/JeonjuGak/JeonjuGak-Bold.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/JeonjuGak/JeonjuGak-Bold.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/JeonjuGak/JeonjuGak-Bold.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/JeonjuGak/subsets/JeonjuGak-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/JeonjuGak/subsets/JeonjuGak-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "Jeonju Gak", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
[전주완판본체 지적 재산권에 대한 안내] 
 
① 전주완판본체 6종에 대한 지적 재산권은 ‘전주시청’에 있습니다. 
 
② 전주완판본체는 개인 및 기업 사용자에게 무료로 제공되며, 모든 출판물과 저작물에서 자유롭게 사용이 가능합니다. 
 
단, 저작권 보호 문화를 위해 글꼴의 사용시 글꼴 출처를 표기하는 것을 권장합니다. 
 
③ 사용자들은 전주완판본체를 자유롭게 배포할 수 있으나, 상업적인 목적으로는 배포 및 수정할 수 없습니다.
```
