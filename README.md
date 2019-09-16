
# 1. 헤더 (header)

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

```
[Google](http://www.google.com "구글")
[Naver](http://www.naver.com "네이버")
[Github](http://www.github.com "깃허브")
```
[Google](http://www.google.com "구글")

[Naver](http://www.naver.com "네이버")

[Github](http://www.github.com "깃허브")

구글 <www.google.com>

네이버 <www.naver.com>

깃허브 <www.github.com>

Jinkyukim Mail <jinkyukim.dev@gmail.com>


## 6.2. 내부 링크 Internal (Anchored) Links

[1. 헤더 Header](#1.-헤더-(header))
[2. 인용문 (Blockquote)](#2.-인용문-(blockquote))





# 7. 테이블 Tables

테이블 생성

Header1|Header2
---|---
Content1|Content2
Content3|Content4
Content5|Content6
Content7|Content8


```
테이블 생성
Header 1 | Header 2
---|---
Content 1 | Content 3
Content 2 | Content 4
```

테이블 정렬

Header 1 | Header 2 | Header 3
:--- | :---: | ---: 
Left | Center | Right 
1|2|3
4|5|6
7|8|9


```
테이블 정렬
Header 1 | Header 2 | Header 3 
| :--- | :---: | ---: |
Left | Center | Right 
1|2|3
4|5|6
7|8|9
```


# 8. 이미지 Adding Images

## 8.1. 인라인 이미지

![alt 토마토](/img/tomato.jpg)

```
인라인 이미지 
![alt text](/test.png )
```

## 8.2. 링크 이미지

![alt Concrete Buildings](https://github.com/jinkyukim-me/open-tutorial/blob/master/img/concrete_building.jpg)
```
링크 이미지
![alt text](image_URL)
```

## 8.3. 참조 이미지

![alt Man][1]

[1]: img/man_laptop.jpg

```
참조 이미지
![alt text][1]
[1]: /test.png
```


# 9. soqn
