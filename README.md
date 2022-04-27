# 제목(Header)

# 제목 1
## 제목 2
### 제목 3


# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세



# 줄바꿈(Line Breaks)

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세



# 강조(Emphasis)

_이탤릭_  
**두껍게**  
**_이탤릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>  



# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록(들여쓰기 두 번)
    1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록



# 링크(Links)

<a href="https://google.com">GOOGLE</a>

[GOOGLE](https://google.com)

<a href="https://naver.com" title="NAVER로 이동!">NAVER</a>

[NAVER](https://naver.com "NAVER로 이동!")

<a href="https://naver.com" title="NAVER로 이동!" target="_blank">NAVER</a>



# 이미지(Images)

![HEROPY](https://heropy.blog/css/images/logo.png)

이미지를 누르면 주소로 이동

[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/)



# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)

> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중중첩된 인용문



# 인라인(inline) 코드 강조

CSS에서 `background` 혹은 `background-image` 속성으로
요소에 이미지를 삽입할 수 있습니다.



# 블록(block) 코드 강조

```html
<a href="https://naver.com" title="NAVER로 이동!" target="_blank">NAVER</a>
```

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```javascript
function func() {
  var a = 'AAA';
  return a;
}
```

```bash
$ git commit -m "Study Markdown"
```

```plaintext
동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세
```



# 표(Table)

position 속성

값 | 의미 | 기본값
--|:--:|--:
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X



# 원시 HTML(Raw HTML) : 마크다운에서 HTML 사용하는 것

동해물과 <u>백두산</u>이 마르고 닳도록<br/>
하느님이 보우하사 <span style="text-decoration: underline;">우리나라</span> 만세



# 수평선(Horizontal Rule)

---

***

___