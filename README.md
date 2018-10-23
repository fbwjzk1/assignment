제목 Headers
#으로 시작하는 텍스트.
#은 하나부터 여섯개까지 쓸 수 있고, #이 늘어날때마다 제목의 수준은 내려간다.
(보통 글씨 크기가 작아진다.)
# h1
## h2
### h3
#### h4
##### h5
###### h6

또는 -, =을 이용하여 h1, h2를 쓸 수 있다.

h1
===
h2
---

## 인용 Blockquotes
>으로 시작하는 텍스트

> 인용문
>> 인용문안의 인용문

## 코드 블럭 Code Blocks
``` 혹은 ~~~ 코드 첫 줄과 마지막 줄에 Back quote ( ` ) 또는 물결( ~ ) 3개 삽입

```
이것은
코드 블럭
입니다
```

~~~
이것은 
코드 블럭
입니다
~~~

```c
void f()
    printf(%s,“이것은 c 코드 입니다”);
}
```

## 인라인 코드 Inline Code Blocks
`(Back quote)로 감싸진 텍스트

 `인라인 코드 블럭`

## 강조 Emphasis
기울여 쓰기(italic) : * 또는 _로 감싼 텍스트
굴게쓰기(bold) : ** 또는 __로 감싼 텍스트

*기울여쓰기(italic)*
_기울여쓰기(italic)_

**굵게쓰기(bold)**
__굵게쓰기(bold)__

## 수평선 Horizontal Rules
- 또는 * 또는 _ 을 3개 이상 작성
(단, -을 사용할 경우 header로 인식할 수 있으니 이 전 라인은 비워두어야한다.)

---
***
___

## 링크 Links
### 외부 링크 External Links
[링크](http://example.com "링크 제목") 인라인 링크
[링크1][1] [1]: http://example1.com/ "링크제목1" 참조 링크
<example.com/> <example@example.com> url 링크

### 인라인 링크
[Google](http://www.google.co.kr “구글”)

[Google][1]
[Naver][2]
[1]: http://google.com/ “구글”
[2]: http://naver.com/ “네이버”











