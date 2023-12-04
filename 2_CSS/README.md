# CSS (Cascading Style Sheet)

- 웹 페이지의 표현(디자인)을 나타내는 언어
- 특정 요소를 선택해서 원하는 "스타일"과 "기능"을 적용 시킬 수 있음

```css
선택자 (누구한테) {
  속성(어떤효과): 값(얼마큼);
}
```

## 스타일 적용 방법

### 내부 방식

1. 인라인 방식

```html
<태그 style="속성:값; 속성:값;"></태그>
```

2. 내부 스타일 방식

```내부 스타일
<head>
    <style>
        선택자 {
            속성 : 값;
            속성 : 값;
        }
    </style>
</head>
```

### 외부 방식

3. 링크 방식

```html
<head>
  <link rel="stylesheet" type="text/css" href="style.css" />
</head>
```

```css
선택자 {
  속성: 값;
}
```
