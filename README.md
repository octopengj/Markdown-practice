# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

# 문장(Paragraph)

가나다라마바사
아자차카타파하

# 줄바꿈(Line Breaks)

가나다라마바사아  (띄어쓰기 2번)  
아자차카타파하

가나다라마바사아`</br>`</br>
아자차카타파하

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


- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록


# 링크(Links)

<a href="https://google.com">GOOGLE</a>

[GOOGLE](https://google.com)

<a href="https://google.com"
title="GOOGLE로 이동!">GOOGLE</a>

[GOOGLE](https://google.com "GOOGLE로 이동!")


# 이미지(Image)

- 사용법 `![대체택스트](링크주소)`

![사과홈](https://cdn.pixabay.com/photo/2015/02/13/00/43/apples-634572_960_720.jpg) 


- 이미지를 링크걸기
    - 사용법 `[이안에 전체를 넣기](링크주소)`

[![사과홈](https://cdn.pixabay.com/photo/2015/02/13/00/43/apples-634572_960_720.jpg)](http://pixabay.com)


# 인용문(BlockQuote)

> 인용문 인용문 인용문

- 중첩 가능
> 인용문
>> 인용문
>>> 인용문
>>>> 인용문


# 인라인(inline) 코드 강조

인라인 코드 강조 `color`


# 블록(block) 코드 강조

```html
<div>code 들어감</div>
```

```css
div {
  color: #fff;
}
```

```javascript
function func() {

}
```

```bash
$ git init
```

```plaintext
가나다라마바사아자차카타파하
```


# 표(Table)

position 속성

값 | 의미 | 기본값
--|--|--
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

- 기본적으로 왼쪽 정렬
- 가운데 정렬

값 | 의미 | 기본값
-- | :--: | --
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

- 오른쪽 정렬

값 | 의미 | 기본값
--|--|--:
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X  


# 수평선

---

***

___




# 원시 HTML(Raw HTML)

- 밑줄

    가나<u>다라마</u>바사아 </br> 자차카타파하

    가나<span style="text-decoration: underline;">다라마</span>바사아

- 타겟

    <a href="https://google.com" title="google로 이동!" target="_blank">GOOGLE</a>

- 이미지
  - 사이즈 조정할 때

    <img width="70" src="https://cdn.pixabay.com/photo/2015/02/13/00/43/apples-634572_960_720.jpg" />
