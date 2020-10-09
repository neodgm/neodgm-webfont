# NeoDGM Web Font Kit

[![jsDelivr](https://data.jsdelivr.com/v1/package/gh/Dalgona/neodgm-webfont/badge)](https://www.jsdelivr.com/package/gh/Dalgona/neodgm-webfont)

이 Git 저장소는 Neo둥근모와 Neo둥근모 Code를 CDN(Content Delivery Network)을
통해 손쉽게 웹 폰트로 사용할 수 있게 해 주는 저장소입니다.

## 사용법

1. `<link>` 태그, 또는 `@import` CSS 규칙을 사용하여 스타일시트를 로드하세요.

    ```html
    <!-- Neo둥근모 -->
    <link rel="stylesheet" href="//cdn.jsdelivr.net/gh/Dalgona/neodgm-webfont@1.510/neodgm/style.css">

    <!-- Neo둥근모 Code -->
    <link rel="stylesheet" href="//cdn.jsdelivr.net/gh/Dalgona/neodgm-webfont@1.510/neodgm_code/style.css">
    ```

    ```css
    /* Neo둥근모 */
    @import url('//cdn.jsdelivr.net/gh/Dalgona/neodgm-webfont@1.510/neodgm/style.css');

    /* Neo둥근모 Code */
    @import url('//cdn.jsdelivr.net/gh/Dalgona/neodgm-webfont@1.510/neodgm_code/style.css');
    ```

2. 이제 여러분의 웹 페이지에서 웹 폰트를 사용할 수 있습니다.

    ```css
    .font-neodgm { font-family: 'NeoDunggeunmo'; }

    .font-neodgm-code { font-family: 'NeoDunggeunmo Code'; }
    ```

## 참고 링크

- [Neo둥근모 프로젝트 공식 웹 사이트](https://neodgm.dalgona.dev)
- [Neo둥근모 GitHub 저장소](https://github.com/Dalgona/neodgm)

## 라이선스

Copyright &copy; 2020, Eunbin Jeong (Dalgona.) &lt;me@dalgona.dev&gt;

이 저장소를 통해 제공되는 모든 글꼴 파일과 웹 폰트 키트에는 SIL Open Font
License 1.1이 적용됩니다. `LICENSE.txt` 파일에 이 라이선스의 전문이 저장되어
있습니다.
