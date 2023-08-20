---
layout: single
title:  "js_destructingAssignment"
---

#js  #js_destruectringAssignment

**구조 분해 할당**

구조 분해 할당 구문은 배열이나 객체의 속성을 분해해서 그 값을 변수에 담을 수 있게 하는 표현식

배열 구조 분해

let [x,y] = [1,2];

clg(x); //1
clg(y); //2
----
배열 구조 분해: 일부 반환값 무시
a,,c
----
배열 구조 분해: 바꿔치기 
a=1 b=2 에서 서로 바꾸려할 경우 
일반 경우에는 새로운 변수 c를 만들어 값을 옮겨야하지만 구조 분해 할당을 사용하면 간단하게 가능하다.
[a,b] = [b,a] 

-----
객체 구조 분해 
let user = {name: ‘yeon’ , age:30};
let {name,age} = user; 


#hello 
good man @
