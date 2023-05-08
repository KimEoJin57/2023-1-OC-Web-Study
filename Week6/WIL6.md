
---
Week6 WIL
---
---
---

우리가 보는 웹 페이지는 요소들이 모여 형성됨.

## BOXMODEL:요소는 어떻게 이루어지는가?
---  
   ### CONTENT  
   what is CONRENT?    
   말하고자 하는 내용물 그 자체를 말한다.  
   ### PADDING  
   what is PADDING?  
   우리가 아는 패딩과 같은 뜻! contents와  border사이의 간격이다.  
   ### BORDER  
   what is BORDER?
   영어의 border뜻 그대로, 테두리라는 의미를 가진다.
   none,botted,dashed 이 3가지를 가장 많이 씀(다른건 영 디자인이 좀..)
   ### MARGIN
   what is MARGIN?
   마진이 남는 다는 말처럼, 남겨둔(?) 무엇인가..   
   여기서는테두리와 다른 요소와의 간격을 말한다.

  
## flexboxlayout:아이템 배열 결정!  
  개구리 게임 하면서 배운점 정리
  ---
   ### justify content
   flex-start: 요소 왼쪽 정렬
   flex-end: 요소 오른쪽 정렬
   center: 요소 가운데 정렬
   space-between: 요소 사이 동일 간격
   space-around: 요소 주위 동일 간격
   
   ### align-items:
   flex-start: 요소 꼭대기로 정렬
   flex-end: 요소 바닥 정렬
   center: 요소 가운데 정렬
   baseline: 시작 위치 정렬
   stretch: 요소들을 컨테이너에 맞도록 늘림

   ### flex-direction  
   row: 가로로 순서대로
   row-reverse: 가로로 거꾸로
   column: 세로로 순서대로
   column-reverse: 세로로 거꾸로
   
   ### flex-wrap
   nowrap: 모든 요소들을 한 줄에 정렬
   wrap: 요소들을 여러 줄 걸쳐 정렬
   wrap-reverse: 여러 줄, 거꾸로 정렬