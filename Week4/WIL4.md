
---
#Week4 WIL
---
---
---
  

아직 GIT 활용 방법을 잘 모르겠어서 과제 제출부터 난관이지만..   
열심히 해보겠습니다..!  
(시험 끝나면 따로 공부해야겠어요..ㅜㅜ)  
  
    
##timotht burners lee, 그는 누구인가?   
---
  
  
    -HTML(Hyper Text Markup Language) > web  
    -HTTP > //붙이지 말걸!! 농담도 함  
    -WWW > World Wide Web  
    (마치 연결된 모양이 거미줄 같다해서 이름붙임)  
  
  


##html(=웹문서)의 구조
---
  
    -<head>(머리부)와 <body>(몸체부)로 구분됨
      
####<head>(머리부)
    -<head> 태그 영역
    -문서의 형태, 타이틀 정보, 스타일 정보, 자바스크립트에 대한 정보가 들어가는 부분
    -웹 브라우저가 알아야 할 중요한 정보들이 들어가는 곳
    
####<body>(몸체부)
    -<body>태그 영역
    -정보 전달을 위한 데이터가 들어가는 부분
    -화면에 직접 출력되는 부분
    
####HTML의 구성요소  
  
######요소(elements)    
    -html에서 시작태그와 종료태그로 이루어진 모든 명령어들  
    -태그명령어 종류들  
  
######태그(tag)      
    -요소의 하나  
    -시작태그와 동료태그로 이루어짐  
    -ex: <h2>나는 김어진이지롱</h2>  
  
######속성(attributes)      
    -더 구체화된 명령어  
    -요소의 시작 태그안에 사용되어짐  
    -다양한 효과 부여  
  
######값(arguments)    
    -속성과 관련된 값 의미


  

##table tag(표)  
---
    
###1. 기본
    <table> 태그는 HTML문서에서 표를 만드는 태그이다.
        -표의 행 : <tr>
        -표의 열 : <td>
    <tr>안에<td>를 넣어서 만든다고 이해하자..!
    
###2.표의 구성(심화)
    -제목은 <thead>,<tbody>,<th>태그를 사용하여 구현한다.
    -<thead>는 표의 제목 영역을 나타낸다(<table>밑,<tr>위 위치함)
    -<tbody>는 표의 본문 영역을 나타낸다(<thead>와 같은 위치)
    -<th> 태그는 제목 셀을 나타내고, <td>는 태그 대신 사용한다
    
###3.표의 병합
    -colspan은 <td>태그에서 사용하며, 열을 확장한다. (좌우)
    -rowspan은 <td>태그에서 사용하며, 행을 확장합니다.(상하)
    -여기서 개인적으로 의문이 하나 드는에데, 그럼 왜 <tr>이 존재하는 걸까..?
  
  
  
##border attribute(테두리)  
---
    
###1. 테두리(border)  
    border 속성은 내용(content)과 패딩(padding) 영역을 둘러싸는 테두리의 스타일을 설정합니당.  
  
###2.border-style    
    - dotted : 테두리를 점선으로 설정함.  
    - dashed : 테두리를 약간 긴 점선으로 설정함.  
    - solid : 테두리를 실선으로 설정함.  
    - double : 테두리를 이중 실선으로 설정함.  
    - groove : 테두리를 3차원인 입체적인 선으로 설정하며,border-color 속성값에 영향을 받음.  
    - ridge : 테두리를 3차원인 능선효과가 있는 선으로 설정하며, border-color 속성값에 영향을 받음.  
  
      
###3.border-color 
<style.> (스타일 옆에 .은 빼고 생각하기)

    .red { border-color: red; }
  
    .green { border-color: rgb(0,255,0); }
  
    .blue { border-color: #0000FF; }
  
    .mix { border-color: red green blue maroon; }
  
    .color { color: teal; }
  
</style>
>예시로 가져옴
