# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks)

띄어쓰기 2번 혹은 <br/> 입력

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려강산  
대한 사람 대한으로 길이 보전하세

# 강조(Emphasis)

_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>  

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크(Links)

<a href="https://google.com">GOOGLE</a>

[GOOGLE](https://google.com)

<a href="https://naver.com"
title="NAVER로 이동!">NAVER</a>

[NAVER](https://naver.com "NAVER로 이동!")

<a href="https://naver.com"
title="NAVER로 이동!"
target="_blank">NAVER</a>  
새창으로 열리는 target은 Markdown에서 지원하지 않는다
뒤에 가서 원시 HTML에서 다시 배운다.

# 이미지(Images)

![]()

![STARBUCKS LOGO](https://inspiring-praline-734634.netlify.app/images/starbucks_logo.png)

링크와 이미지 의 차이는 맨 앞에 느낌표가 있느냐 없느냐 이다.

[![STARBUCKS LOGO](https://inspiring-praline-734634.netlify.app/images/starbucks_logo.png)](https://inspiring-praline-734634.netlify.app/)  

이미지 선택시 기입한 주소로 이동 가능  

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)

> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중중첩된 인용문 1  
>>> 중중첩된 인용문 1  
>>> 중중첩된 인용문 1

# 인라인(Inline) 코드 강조


CSS에서 `background` 혹은
`background-image` 속성으로 요소에 배경
이미지를 삽입할 수 있습니다.

# 블럭(Block) 코드 강조

html
```html
<a href="https://google.com"
target="_blank">GOOGLE</a>
```

css
```css
.list > li {
  position: absolute;
  top: 40px;
}
```

javascript
```javascript
function func() {
  var a = 'AAA';
  return a;
}
```

터미널 입력
```bash 
$ git commit -m 'Study Markdown'
```

일반 텍스트 입력
```plaintext
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
```

# 표(Table)

position 속성

값 | 의미 | 기본값
--|--|:--:
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

# 원시 HTML(Raw HTML)

동해물과 <u>백두산</u>이 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세

동해물과 <span style="text-decoration: underline;">백두산</span>이 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세


<a href="https://naver.com"
title="NAVER로 이동!"
target="_blank">NAVER</a>  

---
<img width="250" src="https://inspiring-praline-734634.netlify.app/images/starbucks_logo.png"
alt=STARBUCKS />

# 수평선(Horizontal Rule)

---
***
___