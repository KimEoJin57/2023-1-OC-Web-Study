#Week3 WIL
---
이번 수업은 개인적으로 이해가 너무 어려워서 최대한 관련 내용을 포함하여 조사해왔다.

##GIT 용어 정리
---
  -git init > 폴더 생성
    
  -git status
    :파일의 상태를 확인하는 명령어
     커밋된 파일 & 스테이지에 있는 파일 : tracked
     그 외 : untracked
  -git add
     :작업 폴더에서 작업한 변경을 stage에 올릴 때 사용하는 명령어. 파일이 tracked 상태가 됨.
     ex) git add 파일1,파일2
         git add.
    
  -git commit
     :git add 명령어로 스테이지에 추가한 수정 파일을 git 저장소에 저장
     주의! 스테이지에 올려놓지 않은(untracked) 파일은 커밋되지 않dma
     ex)git commit -m "커밋메시지"
  -git push
     :commit한 파일을 원격 저장소에 올리는 명령어
     ex) git push 원격 저장소이름 브랜치이름
  -git fetch
     :로컬에는 없지만 원격 저장소에 올라가 있는 데이터를 모두 가져옴(업데이트라고 보면 됨)
     git fetch 원격저장소이름
  -git pull
     :원격 저장소의 데이터를 가져오고, 자동으로 현재 작업하는 로컬 브랜치와 merge(fetch + merge)
  -git merge
     :브랜치 병합, 현재 작업 중인 브랜치에 합칠 커밋을 지정해서 병합
      <commit> 위치에는 주로 병합할 branch 이름을 넣는다.
  -git checkout 브랜치이름
    :브랜치 전환
    

##COMMIT MESSAGE CONVENTION
---
###COMMIT MESSAGE CONVENTION이란?
  -commit을 할때 어떤 유형의 수정인지 표기, 어쩐 사항을 왜 변경했는지 개발자 본인 혹은 동료 개발자가 나중에 보기 편하도록 적는거임
###COMMIT MESSAGE CONVENTION의 구성
  -제목(type : subject)
  -body
  -footer

  
###commit type
  -feat: 새로운 기능 추가
  -fix : 버그 수정
  -docs : 문서수정
  -style : 코드 포멧팅,세미콜론 누락,코드변경이 없는경우
  -refractor : 코드 리펙토링
  -test :테스트 코드,리펙토링 테스트 코드 추가
  -chore : 빌드 업무 수정, 패키지 매니저 수정
  
###subject
  -50자 이하로 작성
  -마침표 붙이지 않음
  -대문자로 작성
  -과거시제가 아닌 명령형으로
###body
  -선택사항으로 작성
  -부연설명이나 커밋의 이유 설명
  -72자 이하

###footer
  -선택사항으로 작성
  -issue traker id작성할때 사용
