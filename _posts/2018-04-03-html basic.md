---
title: 1장 Html의 기초
date: 2018-04-02 23:30:22
description: html의 기본 구조, 태그의 종류와 속성들에 대해 알아봅시다.
categories:
- html
- css
- setting
tags:
- html
- MJworld
---



### 1장 Html 기본 태그 종류와 속성들




# DTD 선언

HTML 4.01의 문서 형식은 Strict, Transitional, Frameset으로 나뉜답니다.


`(1)strict 선언`

strict 선언은 효과 위주의 마크업 태크들(< b >,< i > 등)을 금지해요.

~~~
    <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN"
     "http://www.w3.org/TR/html4/strict.dtd">
~~~

`(2)loose 선언`

loose하게 선언은 strict에서 금지된 태그를 허용해요.

~~~
    <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN"
     "http://www.w3.org/TR/html4/loose.dtd">
~~~



`*(3)frameset 선언*`

frameset 선언은 프레임 구조를 지원합니다.

~~~
    <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Frameset//EN"
     "http://www.w3.org/TR/html4/frameset.dtd">
~~~
 
이 링크를 통해 테스트를 바로 해볼 수 이습니다. __[요기](http://dalidator.kldp.org/)__
 

`(4)html5 선언 선언`
 
하지만 요즘은 간단하게 html 선언 요렇게 짠!

~~~
    <!DOCTYPE html>
~~~
 

# html 태그의 종류들

태그의 종류에는 홀 태그와 쌍 태그로 나뉩니다.


`(1) 홀 태그의 종류`
 
< br/> < hr/> < meta/>
<br>
html5 에서는 닫는 태그 외에도 역슬래시 (/)가 필요하다.

`(2) 쌍 태그의 종류`

< center> < /center> , < ul> < /ul> , < p> < /p>
< li> < /li> , < h1> < /h1> , < div> < /div> , < span> < /span><br>
등 정말 많이 있는데, 나중에 홈페이지 베껴보면서 다 하나씩 써볼게요!

우선 쌍 태그와, 홀 태그로 나뉘어진다는 것만 기억!

# 태그의 속성

`(1)Inline 태그`
 
특징: 아래로 떨어지지 않고 옆으로 계속 붙여서 쓸 수 있는 것이에요! <br>
예시) < span> </ span> < img/>


`(2)Block 태그`

특징: 아래로 떨어지는 태그 다음 요소들은 밑으로 떨어진다! <br>
예시) < p> < /p> ,  < ul> < /ul> 등! 

어떻게 활용하는지 한번 천천히 알아봅시다! <br>
　우선, 속성중에서는 **inline태그** 와 **block태그**가 있다는 것을 기억!



# html의 기본 구조


``` 
    <!DOCTYPE html> 
<html>
　　 <head>
　　　   <meta charset="utf-8">
　　　    <title> Hello </title>
　　  </head>
　　  <body>
　　　    <p> Hello, Welcome to MJworld </p>
　　　  </body>
</html>
```
 

###### header 안에는 title 태그가 들어간다.

`(1)title이 중요한 이유`
 
웹 검색을 하게 되면, 웹 크롤러가 긁어가는 부분이 title 부분이에요.
이 title을 어떻게 넣어주느냐에 따라서 마케팅 할 때 주요 요소로 쓰입니닷
즐겨찾기에 추가할 때도, 이 title이 주요 역할을 하죠.

`(2)meta 태그의 속성들`
 
generator와 Author는 크게 중요하지 않은 부분이라고 하네요. <br>
 어떤 작업 툴을 썼는지를 나타낸다고 합니다.

 하지만, keyword 와 description 는 중요합니다 
 왜? 검색엔진 웹 크롤러가 얘네를 긁어가기 때문에 이 부분을 신경써주어야 검색엔진에 쉽게 노출 될 확률이 높아지는거죠!

홍보,마케팅에 매우 유용하게 쓰이기 때문에 반드시 마크업을 해주어야한다.

# html 태그의 사용 예시 

`(1)a href와 img 태그의 사용`




![image](https://user-images.githubusercontent.com/20442104/38254842-378abd4c-3795-11e8-81f1-fb386e93b5c3.png)

위 그림처럼 보통 < img src= 기본 속성 alt="로고" > 형태로 작성합니다.



속성을 넣어 둔 다음에 지속적으로 다른 속성을 추가할 수 있습니다.
또한 width , height 는 기본적으로 알아야 가로, 세로를 조정할 수 있습니다.

**Tip1** 이미지 업로드 시 테두리 제거 

img 태그의 속성에 border = 0 으로 설정! 


**Tip2** 링크 클릭시, 새 탭으로 연결하기 

a 태그의 속성에 target이라는 곳에 _blank를 해준다. 



오늘은 html 첫시간이었습니다.
 간단한 html 구조와 기본 속성에 대해 알아보았습니다.

다음은 html의 table에 대해서 만나봅시다.

 

