
# __[MARKDOWN Tutorial]__
---

## _Make Title_
***
`<h1>` 부터 `<h6>` 로 표현된다.

#  `#`한 개는 제목 크기가 가장 큼

## `##` 두개 부터
### `###`세개
#### `####`네개
##### `#####` 다섯개
###### `######`여섯개까지 글씨 크기 조정 가능

####### 일곱개부터는 안됨ㅋㅋ루삥뽕


---

## _Emphasis (강조)_
---

각각 `<em>` , `<strong>`, `<del>` 태그로 변환된다.

밑줄은 `<ul></ul>` 태그를 사용하자.


<br>

일반 서체는 아무 표시 필요 없고

*Italic* 서체는 _별('*') 한 개_ 혹은 *언더바 ('_') 한 개*  <br>    `*Italic* 혹은 _Italic_`

**Bold** 서체는 __별('*') 두 개__ 혹은 **언더바 ('_') 두 개**<br>    `**Bold** 혹은 __Bold__`

***Italic-Bold*** 서체는 ___별('*') 세 개___ 혹은  ***언더바('_') 세 개***<br>    `***Italic-Bold*** 혹은 ___Italic-Bold___`

**취소선(canceled line)** 은 ~~물결표(~) 두개~~
**밑줄** 은 <u> 양 옆으로 `<u>` 와 `</u>` 추가</u>
<br>    `~~canceled~~  / <u>underline</u>`


---

### Blockquotes (인용구)
---
`<blockquote>` 태그로 변환됩니다.     






> __인용문__
>> __인용문 안의 인용문__
>>> __인용문 안의 인용문에 하나 더__






---

### List (목록)

---


`<ol>, <ul>` 목록 태그로 변환됩니다.


* 별 한개는  점
  * 띄어쓰기 두번(혹은 Tab키)하면 하위항목
    * 하위의 하위항목도 되나
      * 이것도 되냐
        * 아 잘되네 ㅋㅋㅋ
          * 하위 ㅋㅋ

* **How to coding so good**
  1. Suicide
  2. Reborn
  3. But you cant coding well
  1000. So just fuck off on this field :)
  1200020. 처음에 `1.`으로 list를 시작하면<br> 이후의 순서도 __알아서__ 맞춰진다.


---

Link (링크)
---

`<a>` 로 변환된다.


__[Google](https://google.com)__

__[링크이름]__ 과 __(링크주소)__ 를 반드시 붙여주자!

__[Naver](https://naver.com "링크 설명(title)을 작성하세요!")__

__[링크이름]__ __(링크주소 "링크에 대한 설명")__ 으로 링크 설명을 작성한다

__[yahoo][yahoo link]__

[yahoo link]: https://www.yahoo.com/

__[링크이름]__ __[참조링크]__
문서 안에서 __[참조링크]: 링크__ 를 추가하여 반복 사용가능


<br>

---

## Image (이미지)
---
`<img>` 로 변환된다.


![naver logo](https://customer-service.xyz/wp-content/uploads/2019/12/naver-logo.jpg "네이버 로고")

__`![대체 텍스트](이미지 링크)"이미지 설명"`__ 의 형식으로 작성

<br>

### Link with Image

[![kakao](https://t1.daumcdn.net/cfile/tistory/99E01C485ED7124108 "카카오로 이동합니다.")](https://www.kakaocorp.com/)

__`[![대체 텍스트](이미지 링크"이미지 설명")(링크 주소)]`__ 의 형식으로 작성

<br>


---
## Code-Emphasis
---

__`<pre>`__, __`<code>`__ 로 변환됩니다.
<br>

* #### 인라인(inline) 코드 강조
__`강조할 코드`__

__`__ 을 강조할 코드 양 끝에 하나씩 추가한다.

<br>

* #### 블록(block) 코드 강조

```html
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>
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
$ vim ./~zshrc
```

```python
s = "Python syntax highlighting"
print s
```

```
No language indicated, so no syntax highlighting.
But let's throw in a tag.
```

__`__ 을 <u>__세번 이상__</u> 입력 후 코드 종류도 적는다.


<br>

---
## Table (표)
---

__`<table>`__ 로 변환된다.

헤더 셀을 구분할 떄 3개 이상의 __`-`__ (hyphen/dash)기호가 필요하다.
헤더 셀을 구분하면서 __`:`__ (colons)기호로 셀 안의 내용을 정렬할 수 있다.
가장 좌측과 가장 우측의 __`|`__ (vertical bar) 기호는 생략 가능하다.

값 | 의미 | 기본값
---|:--:|---:
`static` | 유형(기준) 없음 / 배치 불가능 | `static`
`relative` | 요소 자신을 기준으로 배치 | |
`absolute`| 위치 상 부모를 기준으로 배치| |
`fixed` | 브라우저 창을 기준으로 배치 |  

아래와 같이 마크다운에서 작성
```
 값 | 의미 | 기본값
---|:--:|---:
`static` | 유형(기준) 없음 / 배치 불가능 | `static`
`relative` | 요소 자신을 기준으로 배치 | |
`absolute`| 위치 상 부모를 기준으로 배치| |
 `fixed` | 브라우저 창을 기준으로 배치 |  

```
<br>

# -END-
