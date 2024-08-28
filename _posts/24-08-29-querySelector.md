---
layout: post
title:  "querySelector 쿼리선택자"
date:   2024-08-29
categories: jekyll update
---

쿼리선택자 5종
- getElementById
- getElementsByClassName
- getElementsByTagName
- querySelector
- querySelectorAll

단수형 -> HTML Element / Node 요소 한개 반환
- getElementById
- qeurySelector

복수형 -> HTML Collection, HTML list, Nodes 요소 여러개 / 전체 반환
- getElementsByClassName
- getElementsByTagName
- querySelectorAll

😀Node : DOM 구성 객체 / HTML 태그요소 (element), 텍스트, 코멘트

1. getElementById
- id로 검색
- 1개 요소 반환 (id의 유일성 이용)
- 반환대상이 여러개일 경우 첫번째 노드만 반환
- 가장 빠름
- DOM생성(웹 파싱) 시 ID는 별도 리스트로 관리

2. MethodChain 메서드체인
document.getElemnetByID('sidebar').getElementsByClassName(' ');   
이런 방식으로 .을 활용해 계속해서 메소드를 작성하는 것을 의미한다.

3. 공백으로 클래스 이름 나열하기
getElementsByClassName('box aside list');

4. 선택한 요소가 HTML Collection이나 list로 반환 시 접근법
document.getElementsByClassName('box_aside list')[0];
document.getElementsByTagName('div', 'li');

5. ES6 업데이트, querySelector
모든 ID, Class, TagName 조건 없이 사용 가능   
- querySelector()는 1개 노드 반환
- querySelectorAll() 모든 노드 반환

document.querySelector('#sidebar .box_aside :first-child');

6. null 값 확인하기
- node, elemnet 형태
const el = querySelector()
if(el == null)
- list, collection 형태
el.length == 0

7. ?연산자
console.log(nodelist[0]?.tagname)

8. 정적 / 동적 요소
get방식 : 동적 요소 반환
selector방식 : 정적 요소 반환

리스트 수정 시 get방식은 자동으로 반영되지만 selector방식은 반영되지 않음

