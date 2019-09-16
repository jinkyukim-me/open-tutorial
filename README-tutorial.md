# 1. 헤더 (Header)

# This is a H1 
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6

> 제목 Headers 
#으로 시작하는 텍스트.
#은 하나부터 여섯개까지 쓸 수 있고, #이 늘어날때마다 제목의 수준은 내려간다.
(보통 글씨 크기가 작아진다.) 

# 2. 인용문 (Blockquote)
> This is a first blockquote.
> > This is a second blockquote.
> > > This is a third blockquote.

인용문은 > 으로 시작하는 텍스트: > 인용문, >> 인용문안의 인용문, >>> 인용문안의 인용문안의 인용문

# 3. 목록 (List)
## 3.1. 순서가 있는 목록
1. 첫번째
2. 두번째
3. 세번째
    1. 첫번째
    2. 두번째
    3. 세번째
        1. 첫번째
        2. 두번째
        3. 세번째
        
> 숫자를 기입하면 ordered list. 들여쓰기 하면 모양이 바뀐다.

## 3.2. 순서가 없는 목록
* Red
* Green
* Blue
+ Red
+ Green
+ Blue
- Red
- Green
- Blue
* 첫번째
* 첫번째.1
    - 두번쨰
    - 두번째.1
    - 두번째.2
        + 세번쨰
        + 세번째.1
        + 세번쨰.2
        + 세번째.3
        
> *, +, - 를 이용해서 unordered list. 들여쓰기를 하면 모양이 바뀐다.

# 4. 코드 (Code)
여기서 부터 코드 블럭:

    코드 코드 코드
```
이것은 코드 블럭
```
~~~
이것도 코드 블럭
~~~
`인라인 코드 블럭`
> 코드블럭: ``` 혹은 ~~~ 코드 첫 줄과 마지막 줄에 Back quote ( ` ) 또는 물결( ~ ) 3개 삽입 
또는 첫 줄과 한 줄 띄우고 indent(4spaces)
>> 인라인 코드 블럭: `(Back quote)로 감싸진 텍스트

# 5. 수평선 (Horizontal Line)
* * *
***
*****
- - -
---------------
~~~
* * *
***
*****
- - -
-------------------
~~~

> 위의 표현은 모두 동일한 수평선을 표현한다.

# 6. 링크 (Anchor)
## 6.1. 외부 링크 External Links
```
[링크](http://example.com "링크 제목") 인라인 링크
[링크1][1] [1]: http://example1.com/ "링크제목1" 참조 링크
<example.com/> <example@example.com> url 링크
```



